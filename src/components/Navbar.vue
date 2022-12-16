<template>
  <nav class="navbar navbar-expand-lg navbar-dark" style="background-color: #2c3e50">
    <div class="container ">
        <a class="navbar-brand fs-3 fw-bolder" href="#">START BOOTSTRAP</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto fs-4 fw-bolder">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">PORTFOLIO</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">ABOUT</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">CONTACT</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
 export default {
   name : 'Navbar'
 }
</script>