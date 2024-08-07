<script setup lang="ts">

</script>
<template>
  <div>
    <header class="bg-transparent absolute top-0 left-0 w-full flex
    items-center z-10">
      <div class="container">
        <div class="flex items-center justify-between relative">
          <div class="px-4">
            <a href="#home" class="font-bold text-lg text-teal-400 block
            py-6">Kulineran</a>
          </div>
          <div class="flex items-center px-4">
            <button id="hamburger" name="hamburger" type="button"
            class="block absolute right-4">
              <span class="hamburger-line"></span>
              <span class="hamburger-line"></span>
              <span class="hamburger-line"></span>
            </button>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>
<style>
.hamburger-line{
  @apply w-[30px] h-[2px] my-2 block bg-slate-800;
}
</style>