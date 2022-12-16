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
      <div v-for="port in portfolios" :style="{background: port.background}" style="width: 330px; height: 240px"
           class="col-4 rounded-1">
        <img :src=port.image class="w-100">
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
      portfolios: [
        {
          image: "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/cabin.png",
          background: "#dc3545"
        },
        {
          image: "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/cake.png",
          background: "#0dcaf0"
        }
        ,
        {
          image: "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/circus.png",
          background: "#212529;"
        }
        ,
        {
          image: "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/game.png",
          background: "#0dcaf0"
        }
        ,
        {
          image: "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/safe.png",
          background: "#0d6efd"
        }
        ,
        {
          image: "https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/submarine.png",
          background: "#adb5bd"
        }
      ]
    }
  }
}
</script>