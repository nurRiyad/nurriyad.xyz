<script setup lang="ts">
const colorMode = useColorMode()
</script>

<template>
  <div>
    <h1 class="text-2xl sm:text-3xl font-bold items-start  pt-2 pb-4">
      Tech Stack
    </h1>
    <div class="overflow-hidden border dark:border-gray-700 shadow rounded-xl">
      <div class="ease-out transition-transform px-5 py-3">
        <div class="grid gap-2 grid-cols-[repeat(auto-fit,_minmax(5rem,_1fr))]">
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:javascript" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:typescript-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:c-plusplus" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:nodejs-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="simple-icons:express" :color="colorMode" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:nestjs" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:vue" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:nuxt-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:react" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:nextjs-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:vitejs" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:pinia" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:react-query-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:cypress-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:cloudflare-workers-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:aws-ec2" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:linux-tux" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="simple-icons:macos" :color="colorMode" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:git-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
          <div class="border dark:border-gray-600 p-2 border-gray-200 bg-gray-100 dark:bg-gray-700 rounded-md flex items-center justify-center">
            <Icon name="logos:docker-icon" class="hover:scale-[1.1] ease-out transition-transform" size="35" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
