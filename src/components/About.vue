<template>
  <div class="container-fluid pb-3" style="background-color: #1abc9c">
    <div class="mt-5 pt-5">
      <div class="display-4 text-center fw-bolder  pt-5 text-white">
        ABOUT
      </div>
      <div class="d-flex gap-4 align-items-center justify-content-center mt-4">
        <div class="wh-line"></div>
        <i class="fa fa-star fs-3 text-white" aria-hidden="true"></i>
        <div class="wh-line"></div>
      </div>
    </div>
    <div class="row text-white px-5 mt-5 fs-5">
      <div class="col-4 ms-auto">
        <p>
          Freelancer is a free bootstrap theme created by Start Bootstrap.
          The download includes the complete source files including HTML, CSS, and JavaScript
          as well as optional SASS stylesheets for easy customization.
        </p>
      </div>
      <div class="col-4 me-auto">
        <p>
          You can create your own custom avatar for the masthead, change the icon in the dividers,
          and add your email address to the contact form to make it fully functional!
        </p>
      </div>
    </div>
    <div class="text-center mt-4 mb-5">
      <button class="btn btn-outline-light p-2 buttonBigger"><i class="fa fa-download text-white" aria-hidden="true"></i>  Free Download!</button>
    </div>
  </div>
</template>

<style scoped>
.wh-line {
  height: 5px;
  width: 10%;
  background-color: white;
}
.buttonBigger{
  font-size: 1.25rem;
  padding: 1rem 1.75rem
}
</style>

<script>
export default {
  name: 'About'
}
</script>