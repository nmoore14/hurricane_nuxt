<template>
    <header class="sticky sm:fixed flex flex-col sm:flex-row w-full sm:items-center md:w-7/12 p-2 z-50 bg-black sm:rounded-br-lg">
      <div class="flex items-center justify-between px-4">
        <div>
          <nuxt-link to="/"><h1 class="text-2xl text-white self-center">Hurricane Cycles</h1></nuxt-link>
        </div>
        <div>
          <button @click="isOpen = !isOpen" type="button" class="sm:hidden block text-gray-500 hover:text-white focus:text-white focus:outline-none">
            <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
              <path v-if="isOpen" fill-rule="evenodd" d="M18.278 16.864a1 1 0 0 1-1.414 1.414l-4.829-4.828-4.828 4.828a1 1 0 0 1-1.414-1.414l4.828-4.829-4.828-4.828a1 1 0 0 1 1.414-1.414l4.829 4.828 4.828-4.828a1 1 0 1 1 1.414 1.414l-4.828 4.829 4.828 4.828z"/>
              <path v-if="!isOpen" fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"/>
            </svg>
          </button>
        </div>
      </div>
      <div :class="isOpen ? 'block' : 'hidden'" class="sm:block items-center">
        <nuxt-link to="about" class="block px-2 py-1 text-white font-semibold rounded hover:bg-gray-800">About</nuxt-link>
      </div>
  </header>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
      isOpen: false
    }
  }
}
</script>

<style scoped>

</style>