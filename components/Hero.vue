<template>
  <div class="text-center flex items-center justify-center pt-10">
    <div class="mx-auto max-w-xl">
      <h1 class="text-4xl font-bold mb-4">
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </h1>
      <p class="text-lg">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic mollitia,
        nemo officiis dignissimos libero aliquam possimus iure cupiditate?
      </p>
      <div class="space-x-1">
        <UBadge color="primary" variant="solid">One</UBadge>
        <UBadge color="purple" variant="solid">IND</UBadge>
        <UBadge color="cyan" variant="solid">ASDF</UBadge>
        <UBadge color="teal" variant="solid">QWERTYUI</UBadge>
      </div>
      <div class="flex py-4 gap-4 items-center justify-center">
        <UToggle v-model="open" class="ring" />
        <UPopover :open="open">
          <UButton
            color="sky"
            label="Open"
            trailing-icon="i-heroicons-chevron-down-20-solid"
          />

          <template #panel>
            <div class="p-4">
              <h1>Thankyou!!</h1>
            </div>
          </template>
        </UPopover>
      </div>
    </div>
  </div>
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps(["namaProp"]);
const open = ref(false);
</script>
