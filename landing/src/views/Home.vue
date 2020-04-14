<template>
  <div class="home">
    <Header/>
    <Me/>
    <Divider/>
    <PuedoHacer/>
    <Divider/>
    <ContactoPrincipal />
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/principal/Header.vue'
import Me from '@/components/principal/Me.vue'
import Footer from '@/components/Footer.vue'
import Divider from '@/components/Divider.vue'
import PuedoHacer from '@/components/principal/PuedoHacer.vue'
import ContactoPrincipal from '@/components/principal/ContactoPrincipal.vue'

export default {
  name: 'Home',
  components: {
    Header, Me, Footer, Divider, PuedoHacer, ContactoPrincipal
  }
}
</script>
