<template>
<section class="py-5">
  <div class="container h-100">
    <div class="row h-100 align-items-center">
      <div class="col text-center">
        <h3 class="font-weight-light  text-orange">{{title}}</h3>
        <br/><br/>
      </div>
    </div>

    <div class="row align-items-center">
      <div class="media-body">
        <h5 class="mt-0 text-orange-subheader text-center">{{subtitle}}</h5>
        <div class="row">
          <div class="col-sm text-center">
            <p>{{msg}}</p>
          </div>
        </div>
      </div>
    </div>

    <div class="row align-items-center">
      <div class="col text-center">
        <button type="button" class="btn btn-primary custom-btn">
          <i class="far fa-envelope fa-lg"></i> Contacta conmigo!
        </button>
      </div>
    </div>

    <div class="row">
      <div class="col text-center">
        <br/>
        <ul class="social-network social-circle">
          <li><a href="https://twitter.com/rauldearriba" class="icoTwitter" title="Twitter"><i class="fa fa-twitter"></i></a></li>
          <li><a href="https://github.com/Radega1993" class="icoGithub" title="Github"><i class="fab fa-github"></i></a></li>
          <li><a href="https://www.youtube.com/channel/UC2rm7J7G3xxghudcoKBj6gg?view_as=subscriber" class="icoYoutube" title="youtube"><i class="fab fa-youtube"></i></a></li>
          <li><a href="https://www.linkedin.com/in/rauldearriba/" class="icoLinkedin" title="Linkedin"><i class="fa fa-linkedin"></i></a></li>
        </ul>
      </div>
    </div>

  </div>
</section>
</template>

<script>
export default {
  data() {
    return {
      title: 'Te puedo ayudar.',
      subtitle: 'Estoy disponible para proyectos freelance.',
      msg: 'Si tienes un proyecto y crees que te puedo ayudar, no dudes en ponerte en contacto conmigo o simplemte dime "hola" para estar en contacto!'
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

.custom-btn {
  background-color: #D6A006;
  border-color: #DEA811;
  outline: none;
  box-shadow: none !important;
}

.custom-btn:hover{
  background: #FDBC08!important;
  outline: none;
  box-shadow: none!important;
}

.custom-btn:active{
  background: #FDBC08!important;
  outline: none;
  box-shadow: none !important;
}

/* Start socila networks */
ul.social-network {
	list-style: none;
	display: inline;
	margin-left:0 !important;
	padding: 0;
}
ul.social-network li {
	display: inline;
	margin: 0 5px;
}

.social-network a.icoGithub:hover {
	background-color: #000000;
}
.social-network a.icoRss:hover {
	background-color: #F56505;
}
.social-network a.icoFacebook:hover {
	background-color:#3B5998;
}
.social-network a.icoTwitter:hover {
	background-color:#33ccff;
}
.social-network a.icoGoogle:hover {
	background-color:#BD3518;
}
.social-network a.icoYoutube:hover {
	background-color:#BD3518;
}
.social-network a.icoLinkedin:hover {
	background-color:#007bb7;
}
.social-network a.icoGithub:hover i, .social-network a.icoRss:hover i, .social-network a.icoFacebook:hover i, .social-network a.icoTwitter:hover i,
.social-network a.icoGoogle:hover i, .social-network a.icoYoutube:hover i, .social-network a.icoLinkedin:hover i {
	color:#fff;
}
a.socialIcon:hover, .socialHoverClass {
	color:#44BCDD;
}

.social-circle li a {
	display:inline-block;
	position:relative;
	margin:0 auto 0 auto;
	-moz-border-radius:50%;
	-webkit-border-radius:50%;
	border-radius:50%;
	text-align:center;
	width: 50px;
	height: 50px;
	font-size:20px;
	background-color: #D6A006;
}
.social-circle li i {
	margin:0;
	line-height:50px;
	text-align: center;
}

.social-circle li a:hover i, .triggeredHover {
	-moz-transform: rotate(360deg);
	-webkit-transform: rotate(360deg);
	-ms--transform: rotate(360deg);
	transform: rotate(360deg);
	-webkit-transition: all 0.2s;
	-moz-transition: all 0.2s;
	-o-transition: all 0.2s;
	-ms-transition: all 0.2s;
	transition: all 0.2s;
}
.social-circle i {
	color: #fff;
	-webkit-transition: all 0.8s;
	-moz-transition: all 0.8s;
	-o-transition: all 0.8s;
	-ms-transition: all 0.8s;
	transition: all 0.8s;
}
/* end socila networks */
</style>
