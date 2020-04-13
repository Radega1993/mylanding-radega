<template>
<!--Section: Contact v.2-->
<section class="mb-4 top-buffer">
  <!--Section heading-->
  <h2 class="h1-responsive font-weight-bold text-center my-4">Conta conmigo</h2>
  <!--Section description-->
  <p class="text-center w-responsive mx-auto mb-5">¿Tienes alguna pregunta?, ¿tienes algun problema?, ¿tienes algun proyecto en que quieras realizar? Contacta conmigo y coactare con usted en la maxima brevedad posible</p>

  <p class="text-center w-responsive mx-auto mb-5">
    O contacta directamente a:
    <a href="mailto:rauldearriba@gmail.com">rauldearriba@gmail.com</a>
  </p>
  <div class="row">

    <!--Grid column-->
    <div class="col-md-12 mb-md-0 mb-5">
      <form id="contact-form" name="contact-form" action="mail.php" method="POST">

        <!--Grid row-->
        <div class="row">

          <!--Grid column-->
          <div class="col-md-6">
            <div class="md-form mb-0">
              <input type="text" id="name" name="name" class="form-control">
              <label for="name" class="">Tu nombe</label>
            </div>
          </div>
          <!--Grid column-->

          <!--Grid column-->
          <div class="col-md-6">
            <div class="md-form mb-0">
              <input type="text" id="email" name="email" class="form-control">
              <label for="email" class="">Tu email</label>
            </div>
          </div>
          <!--Grid column-->

        </div>
        <!--Grid row-->

        <!--Grid row-->
        <div class="row">
          <div class="col-md-12">
            <div class="md-form mb-0">
              <input type="text" id="subject" name="subject" class="form-control">
              <label for="subject" class="">Asunto</label>
            </div>
          </div>
        </div>
        <!--Grid row-->

        <!--Grid row-->
        <div class="row">

          <!--Grid column-->
          <div class="col-md-12">

            <div class="md-form">
              <textarea type="text" id="message" name="message" rows="2" class="form-control md-textarea"></textarea>
              <label for="message">Tu mensaje</label>
            </div>

          </div>
        </div>
        <!--Grid row-->

      </form>

      <div class="text-center text-md-left">
        <a class="btn btn-primary" @click="validateForm">Enviar</a>
      </div>
      <div class="status"></div>
    </div>
    <!--Grid column-->



  </div>

</section>
<!--Section: Contact v.2-->
</template>

<script>
export default {
  name: 'EmailContacto',
}
</script>

<style lang="css" scoped>
  .top-buffer { margin-top:80px; }
</style>
