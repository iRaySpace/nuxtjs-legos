<template>
  <div class="flex h-screen overflow-hidden">
    <aside class="h-screen bg-black w-[18.125rem]">
      <div class="px-6 py-5 text-white">
        Space Admin
      </div>
    </aside>
    <div class="relative flex flex-1 flex-col">
      <header class="sticky top-0 z-999 flex w-full bg-white drop-shadow-1">
        <div class="flex py-4 px-4">
          Header
        </div>
      </header>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
