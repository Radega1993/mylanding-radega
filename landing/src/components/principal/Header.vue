<template>
<!-- Full Page Image Header with Vertically Centered Content -->
<header class="masthead">
  <div class="container h-100">
    <div class="row h-100 align-items-center">
      <div class="col-12 text-center">
        <img alt="Radega logo" src="../../assets/logo.png">
        <h1 class="display-4 text-white">Never give up!</h1>
      </div>
    </div>
  </div>
</header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>
.masthead {
  height: 100vh;
  min-height: 500px;
  background: #000 url('../../assets/fondo.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.masthead:hover {
  height: 100vh;
  min-height: 500px;
  background:
    url('../../assets/fondo.png'),
    radial-gradient(at center, #1D1D95, #000000);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
