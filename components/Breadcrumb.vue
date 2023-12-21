<template>
  <div
    class="fixed top-0 p-6 bg-gray-300 w-full flex items-center justify-between"
  >
    <div class="hidden md:block"><Dropdown /></div>
    <div class="mx-auto"><UBreadcrumb :links="links" /></div>

    <div class="hidden md:block">
      <UInput color="gray" variant="outline" placeholder="Search..." />
    </div>
  </div>
</template>

<script setup>
const links = [
  {
    label: "Home",
    icon: "i-heroicons-home",
    to: "/",
  },
  {
    label: "Navigation",
    icon: "i-heroicons-square-3-stack-3d",
    to: "Navigation",
  },
  {
    label: "Link",
    icon: "i-heroicons-link",
    to: "Link",
  },
];
</script>
