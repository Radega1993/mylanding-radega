<template>
  <div class="container">
    <h1>Información de contacto</h1>
    
    <Contact />
  </div>
</template>

<script>
// @ is an alias to /src
import Contact from '@/components/contact/Contact.vue'
export default {
  name: 'Contact',
  components: {
    Contact
  }
}
</script>
