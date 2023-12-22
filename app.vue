<template>
  <div>
    <!-- Breadcrumb -->
    <div class="py-2">
      <div class="mx-auto">
        <Breadcrumb />
      </div>
    </div>

    <!-- Hero dan Accordion Section -->
    <div class="bg-gray-200 flex items-center justify-center">
      <div class="min-h-screen mx-auto flex justify-between items-center gap-5">
        <div class="flex flex-wrap items-center justify-center">
          <!-- Hero Section -->
          <div class="w-full self-center px-4 py-10">
            <Hero />
          </div>

          <!-- Accordion Section -->
          <div class="px-4 py-10">
            <div class="flex">
              <div class="flex items-center justify-center">
                <div>
                  <div class="flex items-center justify-center">
                    <UAvatar
                      chip-color="red"
                      chip-text=""
                      chip-position="top-right"
                      size="2xl"
                      src="https://avatars.githubusercontent.com/u/739984?v=4"
                      alt="Avatar"
                    />
                  </div>
                  <h1 class="text-center">Lorem ipsum dolor sit.</h1>
                  <div class="space-x-1 flex flex-wrap space-y-1">
                    <UBadge color="primary" variant="solid">One</UBadge>
                    <UBadge color="purple" variant="solid">IND</UBadge>
                    <UBadge color="cyan" variant="solid">ASDF</UBadge>
                    <UBadge color="teal" variant="solid">QWERTYUI</UBadge>
                  </div>
                </div>
              </div>
              <div>
                <Accordion />
              </div>
            </div>
          </div>
          <div class="pb-20">
            <h1 class="text-center">Lorem ipsum dolor sit.</h1>
            <div class="py-2 flex items-center justify-center"><Range /></div>
            <h1 class="text-center">Lorem ipsum dolor sit.</h1>
            <div class="py-2"><Tab /></div>
            <div>
              <UAlert
                description="You can add components to your app using the cli."
                title="Heads up!"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
