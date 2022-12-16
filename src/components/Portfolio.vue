<template>
  <div class="container mb-5 pb-5">
    <div>
      <div class="display-4 text-center fw-bolder mt-5 pt-5">
        PORTFOLIO
      </div>
      <div class="d-flex gap-4 align-items-center justify-content-center mt-4">
        <div class="bl-line"></div>
        <i class="fa fa-star fs-3" aria-hidden="true"></i>
        <div class="bl-line"></div>
      </div>
    </div>
    <div class="row gap-5  justify-content-center mt-5">
      <div v-for="img in images" style="width: 330px; height: 240px"
           class="col-4 rounded-1">
        <img :src=img class="w-100">
      </div>
    </div>
  </div>
</template>

<style scoped>
.bl-line {
  height: 5px;
  width: 10%;
  background-color: black;
}
</style>
<script>
export default {
  name: 'Portfolio',
  data() {
    return {

      images: [
        "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/cabin.png",
        "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/cake.png",
        "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/circus.png",
        "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/game.png",
        "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/safe.png",
        "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/submarine.png"
      ]
    }
  }
}
</script>