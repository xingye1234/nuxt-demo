<template>
  <div class="w-full h-screen bg-gray-200 text-white">
    <header
      class="h-12 bg-gray-300 flex items-center
      px-4 box-border font-bold text-lg"
    >
      <h3 class="mr-10">header</h3>
      <NavBar></NavBar>
    </header>
    <div class="p-4 box-border">
      <NuxtPage />
    </div>
  </div>
</template>
<script setup lang="ts"></script>
