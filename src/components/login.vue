<script>




</script>
<template>
  <div class=" ">
    <form class="w-full max-w-sm">
      <div class="flex items-center border-b border-red-500 py-2">
        <input v-bind="password" v-model="phone" class="appearance-none bg-transparent border-none w-full text-gray-700 mr-3 py-1 px-2 leading-tight focus:outline-none" type="naders"  placeholder="phone" aria-label="Full name">
        <button class="flex-shrink-0 bg-red-500 hover:bg-red-700 border-red-500 hover:border-red-700 text-sm border-4 text-white py-1 px-2 rounded" type="button">
          ورود
        </button>
        <button @click="resetInput" class="flex-shrink-0 border-transparent border-4 text-red-500 hover:text-red-800 text-sm py-1 px-2 rounded" type="button">
          حذف
        </button>
      </div>
    </form>
  </div>
</template>

<style scoped>

</style>