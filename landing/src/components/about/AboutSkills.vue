<template>
<section class="py-5">
  <div class="container">
    <div class="row align-items-center">
      <div class="col text-center margin-top-100">
        <h3 class="font-weight-light  text-orange">{{title}}</h3>
        <p>Soy un chico de 27 años que le apasiona la tecnología el deporte y el emprendimiento. Estoy terminando mi grado en ingeniería informática y
          hago diferentes proyectos en mi tiempo libre.</p>
        <br />
      </div>
    </div>

    <div class="row d-flex justify-content-center">
      <div class="card-deck">
        <div class="card" v-for="(skill, index) in skills" :key="index">
          <img class="card-img-top" :src="skill.img" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title">{{skill.title}}</h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item" v-for="(item, index) in skill.tecno" :key="index">{{item}}</li>
          </ul>
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
      title: 'Mis Skills.',
      skills: {
        frontend: {
          title: 'Frontend',
          img: require('../../assets/about/fe.png'),
          tecno: ['VueJS', 'Javascript', 'Bootstrap', 'HTML/CSS', 'Flutter']
        },
        backend: {
          title: 'Backend',
          img: require('../../assets/about/be.png'),
          tecno: ['Python', 'NodeJS', 'MongoDB', 'SQL']
        },
        otras: {
          title: 'Otras',
          img: require('../../assets/about/ot.png'),
          tecno: ['Unit Testing', 'Balsamiq', 'Wordpress', 'Sysadmin', 'Linux']
        },
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

.margin-top-100 {
  margin-top: 100px;
}

</style>
