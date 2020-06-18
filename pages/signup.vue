<template>
  <div class="relative flex flex-col p-8 justify-center items-center">
    <h1 class="text-white">Sign Up Page</h1>
    <div id="signup-info" class="flex flex-col w-full p-12 justify-around bg-gray-400">
      <div id="benefits-container">
        <h2>Newsletter Benefits</h2>
      </div>
      <NewsletterSignup />
    </div>
  </div>
</template>

<script>
import NewsletterSignup from '~/components/NewsletterSignup.vue';

export default {
  components: {
    NewsletterSignup
  }
}

</script>

<style scoped>
.hbspt-form {
  max-width: 1000px;
  min-width: 500px;
}

.hbspt-form > iframe {
  width: 100%;
}
</style>
