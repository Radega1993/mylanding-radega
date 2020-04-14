<template>
  <div class="about">
    <AboutSkills/>
    <Footer/>
  </div>
</template>

<script>

import Footer from '@/components/Footer.vue'
import AboutSkills from '@/components/about/AboutSkills.vue'

export default {
  name: 'About',
  components: {
    AboutSkills, Footer
  }
}
</script>
