<template>
  <div><UTabs :items="items" /></div>
</template>

<script setup>
const items = [
  {
    label: "Tab1",
    content: "This is the content shown for Tab1",
  },
  {
    label: "Tab2",
    content: "And, this is the content for Tab2",
  },
  {
    label: "Tab3",
    content: "Finally, this is the content for Tab3",
  },
];
</script>
