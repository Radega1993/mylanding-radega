<template>
<section class="py-5">
  <div class="container">
    <div class="row align-items-center">
      <div class="col text-center">
        <img src="../../assets/mec.png" class="rounded-circle" style="width:30%">
        <h2 class="font-weight-light text-orange">{{title}}</h2>
        <p>{{msg}}</p>
      </div>
    </div>
  </div>
</section>
</template>

<script>
export default {
  name: 'Me',
  data() {
    return {
      title: '¡Hola!',
      msg: 'Soy Raul de Arriba y soy desarroyador. Tengo pasión por la tecnología y el deporte, adoro convertir ideas en realidades.'
    }
  }
}
</script>

<style scoped>
.text-orange{
  color: #D6A006;
}
</style>
