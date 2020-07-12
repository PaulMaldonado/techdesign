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
            <div class="d-flex justify-content-center mt-4">
              <a href="https://www.facebook.com/Tech-Design-105226334583577" target="_blank">
                <img src="../assets/facebook-logo.png" alt="facebook" class="facebook-icon">
              </a>

              <a href="https://github.com/PaulMaldonado" target="_blank">
                <img src="../assets/github.png" alt="github" class="github-icon">
              </a>
            </div>
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

  .icon-facebook {
    max-width: 100px;
    height: 150px;
  }

  .facebook-icon {
    width: 50px;
  }

  .github-icon {
    width: 50px;
  }

  .instagram-icon {
    width: 70px;
  }
</style>