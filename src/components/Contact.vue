<template>
  <div class="container mb-5 pb-5">
      <div class="display-4 text-center fw-bolder mt-5 pt-5">
        CONTACT ME
      </div>
      <div class="d-flex gap-4 align-items-center justify-content-center mt-4">
        <div class="bl-line"></div>
        <i class="fa fa-star fs-3" aria-hidden="true"></i>
        <div class="bl-line"></div>
      </div>
    <div class="form-floating m-auto mt-5 fs-5" style="width: 60%">
      <div class="form-floating mb-3">
        <input type="text" class="form-control" id="floatingInputName" placeholder="Enter full name...">
        <label for="floatingInputName">Full name</label>
      </div>
      <div class="form-floating mb-3">
        <input type="email" class="form-control" id="floatingInputEmail" placeholder="name@example.com">
        <label for="floatingInputEmail">Email address</label>
      </div>
      <div class="form-floating mb-3">
        <input type="tel" class="form-control" id="floatingInputPhone" placeholder="name@example.com">
        <label for="floatingInputPhone">Phone number</label>
      </div>
      <div class="form-floating mb-3">
        <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
        <label for="floatingTextarea2">Message</label>
      </div>
      <button class="btn btn-primary btn-submit" type="submit">Send</button>
    </div>
  </div>
</template>

<style scoped>
.bl-line {
  height: 5px;
  width: 10%;
  background-color: black;
}
.btn-submit{
  background-color: #1abc9c;
  color: white;
  font-size: 25px;
  padding: 10px 20px;
}
</style>
<script>
export default{
  name: 'Contact'
}
</script>