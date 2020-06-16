<template>
  <div class="flex flex-col no-wrap mt-64">
    <div class="flex flex-row flex-wrap w-full justify-center text-center bg-gray-900" id="contact-container">
      <div class="mx-8" id="contact">
        <h1 class="text-3xl sm:text-4xl myDisplay-1">Contact</h1>
        <p class="text-white">Phone:</p>
        <a href="tel:(931) 250-7224" class="text-center w-full myDisplay-a">(931) 250-7224</a>
        <p class="text-white mt-2">Email:</p>
        <a href="mailto:hurricanecycles@icloud.com" class="text-center w-full mb-2 myDisplay-a">hurricanecycles@icloud.com</a>
        <p class="text-white mt-2">Address:</p>
        <p class="text-white">138 North Main Street</p>
        <p class="text-white mb-2">Crossville, Tennessee 38555</p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1648327.80103677!2d-84.78911784432124!3d36.20570876123914!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x886750d3c1e15f33%3A0x27cd3c7f1572c924!2s138%20N%20Main%20St%2C%20Crossville%2C%20TN%2038555!5e0!3m2!1sen!2sus!4v1590107837062!5m2!1sen!2sus" width="375" height="300" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0" title="Hurricane Cycles Map"></iframe>		
      </div>
      <div class="mx-8" id="hours">
        <h1 class="text-3xl sm:text-4xl myDisplay-1">Hours</h1>
        <p class="text-lg text-white">Monday: <span class="text-2xl myDisplay-p">Closed</span></p>
        <p class="text-lg text-white">Tuesday: 10:00 AM - 5:00 PM</p>
        <p class="text-lg text-white">Wednesday: 10:00 AM - 5:00 PM</p>
        <p class="text-lg text-white">Thursday: 10:00 AM - 5:00 PM</p>
        <p class="text-lg text-white">Friday: 10:00 AM - 5:00 PM</p>
        <p class="text-lg text-white">Saturday: 10:00 AM - 5:00 PM</p>
        <p class="text-lg text-white">Sunday: <span class="text-2xl myDisplay-p">Closed</span></p>
      </div>
    </div>
    <NewsletterSignup />
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import NewsletterSignup from '~/components/NewsletterSignup.vue'

export default {
  components: {
    Logo,
    NewsletterSignup
  }
}
</script>

<style>

</style>
