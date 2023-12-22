<template>
  <div class="px-4 max-w-xl mx-auto">
    <UAccordion color="violet" :items="items" :class="'max-w-xs'" />
  </div>
</template>

<script setup>
const items = [
  {
    label: "Getting Started",
    icon: "i-heroicons-information-circle",
    content:
      "Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue.",
  },
  {
    label: "Installation",
    icon: "i-heroicons-arrow-down-tray",
    content: "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
  },
  {
    label: "Theming",
    icon: "i-heroicons-eye-dropper",
    content: "Praesent ut sem nec arcu pellentesque aliquet.",
  },
  {
    label: "Layouts",
    icon: "i-heroicons-rectangle-group",
    content:
      "Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue.",
  },
  {
    label: "Components",
    icon: "i-heroicons-square-3-stack-3d",
    content:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit,",
  },
  {
    label: "Utilities",
    icon: "i-heroicons-wrench-screwdriver",
    content:
      " Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. ",
  },
];
</script>
