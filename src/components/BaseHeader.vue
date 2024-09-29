<script setup>
name: "BaseHeader";
</script>

<!--Testing-->
<template>
  <nav
    class="relative flex items-center justify-between px-2 py-3 bg-white mb-3 border-b border-gray-200"
  >
    <div class="container px-4 mx-auto flex items-center justify-between">
      <div
        class="w-full relative flex justify-between items-center lg:w-full px-4 lg:static lg:items-center lg:justify-between"
      >
        <a
          class="text-sm font-bold leading-relaxed inline-block mr-4 py-2 whitespace-nowrap uppercase text-black flex-grow"
        >
          Placeholder
        </a>
        <button
          class="text-sm text-blue-500 cursor-pointer leading-none px-3 py-2 border-2 border-solid border-blue-500 bg-transparent block outline-none flex-shrink-0 hover:border-blue-700 hover:text-blue-700"
          type="button"
          onclick="window.location.href='https://www.google.com'"
        >
          常見問題
        </button>
      </div>
    </div>
  </nav>
</template>
