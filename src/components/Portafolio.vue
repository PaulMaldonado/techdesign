<template>
  <div id="portafolio">
    <div class="mt-5">
      <div class="main">
        <div class="container">
          <h2 class="text-center mt-4 text-portafolio">Portafolio</h2>
          <p class="text-center mt-3 text-portafolio-p">Estos son nuestros proyectos</p>
        </div>

        <div class="container">
          <div class="row mt-5">
            <div class="col-md-6 col-sm-12 col-lg-6 col-xl-6">
             
            </div>
          </div>
        </div>
      </div>
    </div> 
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
  .images-portafolio {
    display: block;
    margin: 0 auto;
    max-width: 100%;
  }

  .main {
    background-image: url("../assets/banner-portafolio.png");
    max-width: 100%;
    height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

  .text-portafolio {
    font-size: 80px;
    font-weight: bold;
    color: white;
  }

  .text-portafolio-p {
    font-weight: 100;
    font-size: 18px;
    color: white;
  }

  .image-cbta {
    width: 500px;
    max-height: 600px;
  }
</style>