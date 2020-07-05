<template>
  <div id="redes-sociales">
    <footer id="footer" class="py-4 b-dark text-white-50 bg-light">
      <div class="container">
        <div class="row">
          <div class="col-md-6 col-sm-12 col-lg-6 col-xl-6">
            <h5 class="footer-content">Tech Design</h5>
            <p class="footer-content-p mt-4">Nos dedicamos al desarrollo y diseño de sitios web, aplicaciones moviles,
            diseño de logotipos, curriculums y mucho más..
            </p>
          </div>

          <div class="col-md-6 col-sm-12 col-lg-6 col-xl-6">
            <h5 class="footer-links">Nuestras Redes sociales</h5>
            <i class="fa fa-facebook-square"></i>
          </div>
        </div>
      </div>

      <div class="container text-center mt-5">
        <small class="copy">© 2020 - 2021 Copyright Tech Design</small>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
  #footer {
    flex-shrink: none;
  }

  .footer-content {
    font-size: 30px;
    font-weight: 300;
    text-align: center;
    color: black
  }

  .footer-content-p {
    font-size: 18px;
    font-weight: 100;
    color: black;
  }

  .footer-links {
    font-size: 30px;
    font-weight: 300;
    text-align: center;
    color: black;
  }

  .copy {
    color: black;
    font-weight: 100;
  }
</style>