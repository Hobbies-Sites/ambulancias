<template>
  <div class="wrapper">
    <div class="bg_special" style="background-image: url(/img/page/ambulance.jpg)"></div>
    <div class="section section-hero section-shaped">
      <div class="shape shape-style-3 shape-default">
        <span class="span-100"></span>
        <span class="span-50"></span>
        <span class="span-100"></span>
      </div>
      <div class="page-header">
        <div class="container shape-container d-flex align-items-center py-lg">
          <div class="col px-0">
            <div class="row align-items-center justify-content-center">
              <div class="col-lg-12 text-center">
                <h1 class="text-white display-1">Asesores Profesionales y Capacitación en Protección Civil 1</h1>
                <div class="btn-wrapper mt-4">
                  <a href="#" class="btn btn-warning btn-icon mt-3 mb-sm-0">
                    <span class="btn-inner--icon"><i class="ni ni-button-play"></i></span>
                    <span class="btn-inner--text">LLAMÁNOS AHORA MISMO</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="separator separator-bottom separator-skew zindex-100">
        <svg x="0" y="0" viewBox="0 0 2560 100" preserveAspectRatio="none" version="1.1" xmlns="http://www.w3.org/2000/svg">
          <polygon class="fill-white" points="2560 0 2560 100 0 100"></polygon>
        </svg>
      </div>
    </div>
    <div class="section features-6" style="background: white">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-6">
            <div class="info info-horizontal info-hover-primary">
              <div class="description pl-4">
                <h5 class="title">Asesores Profesionales y Capacitación en Protección Civil 1</h5>
                <br>
                <p>Somos especializastas en traslado en ambulancias, contamos son los siguientes servicios: </p>
                <div class="list_custom">
                  <p>Ambulancia de urgencia</p>
                  <p>Ambulancia de traslado programado locales y foráneos</p>
                  <p>Ambulancia de traslado sencillo</p>
                  <p>Ambulancia con oxigeno</p>
                  <p>Ambulancia de terapia intensiva</p>
                  <p>Ambulancia para eventos deportivos y culturales</p>
                  <p>Ambulancia para servicios de prevención</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6 col-10 mx-md-auto">
            <img class="ml-lg-5" src="img/ill/ill.png" width="100%">
          </div>
        </div>
        <div class="row">
          <div class="col-sm-12 pt-5 text-center">
            <div class="alert alert-primary" role="alert">
              ¿Necesitas ayuda inmediatamente? - Llámanos ahora mismo - (55) 31 09 43 40
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="section features-1">
      <div class="container">
        <div class="row">
          <div class="col-md-8 mx-auto text-center">
            <span class="badge badge-primary badge-pill mb-3">Servicios</span>
            <h3 class="display-3">Servicio de ambulancias privadas</h3>
            <p class="lead">Contamos con un amplio catálogo de servicios para ofecerte un servicio de calidad, conoce algunos de los servicios más solicitados.</p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <div class="info">
              <div class="icon icon-lg icon-shape icon-shape-primary shadow rounded-circle">
                <i class="fas fa-ambulance fa-2x"></i>
              </div>
              <h6 class="info-title text-uppercase text-primary">Ambulancia con oxigeno</h6>
              <p class="description opacity-8">La ambulancia de traslado con oxigeno, ofrece una tranquilidad para usted y su paciente, ya que la ambulancia cuenta con tanque de oxigeno central y dos tanques de oxigeno portátil. Es decir, estamos preparados para suministrar oxigeno por medio de puntas nasales, mascarilla con o sin reservorio, o a presión positiva. Ademas de ir monitoreando sus signos vitales y su oximetria de pulso.</p>
            </div>
          </div>
          <div class="col-md-4">
            <div class="info">
              <div class="icon icon-lg icon-shape icon-shape-primary shadow rounded-circle moving-ambulance">
                <i class="fas fa-ambulance fa-2x"></i>
              </div>
              <h6 class="info-title text-uppercase text-primary">Ambulancia de traslado sencillo</h6>
              <p class="description opacity-8">La ambulancia de traslado sencillo cuenta con dos paramédicos y un carro-camilla para la comodidad de su paciente, y pueda ser trasladado a su domicilio o a su clínica para consulta.</p>
            </div>
          </div>
          <div class="col-md-4">
            <div class="info">
              <div class="icon icon-lg icon-shape icon-shape-success shadow rounded-circle">
                <i class="fas fa-ambulance fa-2x"></i>
              </div>
              <h6 class="info-title text-uppercase text-success">Ambulancia de terapia intensiva</h6>
              <p class="description opacity-8">Nuestras ambulancias de terapia intensiva cuentan con tecnología avanzada para el traslado en ambulancia de pacientes críticos. Tripulada por médicos y paramédicos con cédula profesional.</p>
            </div>
          </div>
          <div class="col-md-4">
            <div class="info">
              <div class="icon icon-lg icon-shape icon-shape-warning shadow rounded-circle">
                <i class="fas fa-ambulance fa-2x"></i>
              </div>
              <h6 class="info-title text-uppercase text-warning">Renta de ambulancias</h6>
              <p class="description opacity-8">Renta de ambulancias para constructoras, producciones cinematográficas, servicios preventivos de seguridad y salud en el trabajo.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <br /><br />
    <Footer></Footer>
  </div>
</template>

<script>

  import Footer from "../components/Footer/Footer";

  export default {
    components: {
      'Footer': Footer
    }
  }
</script>

<style>

  @keyframes moving {
    0%   {right: -10%}
    50%   {right: 0%}
    100% {right: -10%}
  }

  @keyframes moving-ambulance {
    0%   {left: 15px; bottom: 0px;}
    50%  {left: 15px; bottom: 0px; rotate:20deg}
    75%  {left: 15px; bottom: 0px; rotate:5deg}
    75%  {left: 100px; bottom: 0px;}
  }

  .section-shaped .shape-style-3 :nth-child(2){
    animation: moving ease 10s infinite;
    width: 20%;
  }

  .section-shaped .shape-style-3 :nth-child(4){
    animation: moving ease 10s infinite;
    width: 30%;
  }

  .info .icon{
    position: relative;
  }

  .info .icon i:before{
    position: absolute;
    left: 15px;
    bottom: 0px;
    animation: moving-ambulance infinite ease 15s;
  }

  .bg_special{
    position: absolute;
    z-index: 0;
    width: 100%;
    height: 100%;
    opacity: 0.5;
    background-size: cover;
  }

  .list_custom{
    padding-left: 10px;
  }
  .list_custom p{
    font-weight: bold;
  }

  .info{
    padding: 15px;
  }

</style>
