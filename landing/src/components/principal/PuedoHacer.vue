<template>
<section class="py-5">
  <div class="container">
    <div class="row align-items-center">
      <div class="col text-center">
        <h3 class="font-weight-light  text-orange">{{title}}</h3>
        <br/><br/>
      </div>
      <div class="row">
        <div class="media">
          <img src="../../assets/PuedoHacer/idea.png" class="align-self-start mr-3" style="width:15%" />
          <div class="media-body">
            <h5 class="mt-0 text-orange-subheader">{{datosDerecha.title}}</h5>
            <p>{{datosDerecha.msg}}</p>
          </div>
        </div>
      </div>
      <br/>
      <br/>
      <div class="row">
        <div class="media">
          <div class="media-body">
            <h5 class="mt-0 mb-1 text-orange-subheader text-right">{{datosIzquierda.title}}</h5>
            <p>{{datosIzquierda.msg}}</p>
          </div>
          <img src="../../assets/PuedoHacer/codigo.png" class="align-self-start ml-3" style="width:15%">
        </div>
      </div>
    </div>
  </div>
</section>
</template>

<script>
export default {
  data() {
    return {
      title: 'Que puedo hacer.',
      datosDerecha:{
        title: 'Planificar tu idea.',
        msg: 'Puedo tratar de orientarte en las necesidades para llevar a cabo tus proyectos tecnológicos'
      },
      datosIzquierda:{
        title: 'Desarrollar tu idea.',
        msg: 'Como programador, puedo llevar tu idea desde tu cabeza hasta la realidad, funcionando en los dispositivos necesarios utilizando las últimas tecnologías del mercado'
      }
    }
  }
}
</script>

<style lang="css" scoped>
.text-orange{
  color: #D6A006;
}

.text-orange-subheader{
  color: #DEA811;
}

</style>
