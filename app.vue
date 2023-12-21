<template>
  <div>
    <div><Breadcrumb /></div>
    <div class="flex items-center justify-center bg-gray-200 min-h-screen">
      <div class="top-20 md:top-24 absolute">
        <div class="flex items-center justify-center pb-4 gap-4">
          <Sliderover /> <Command />
        </div>
        <div><Accordion /></div>
        <div class="flex items-center justify-center gap-4 pt-4">
          <UBadge color="indigo" variant="solid">Badge</UBadge>
          <UBadge color="primary" variant="solid">Badge</UBadge>
          <UBadge color="red" variant="solid">Badge</UBadge>
        </div>
      </div>
    </div>
  </div>
</template>
