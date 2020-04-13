<template>
  <div class="home">
    <Header/>
    <Me/>
  </div>
</template>

<script>
import Header from '@/components/principal/Header.vue'
import Me from '@/components/principal/Me.vue'

export default {
  name: 'Home',
  components: {
    Header, Me
  }
}
</script>
