<template>
  <div class="login mt-5">
    <form name="login-form">
      <div class="container mb-3">
        <div class="label-u">
          <label for="email/username">Email / Username </label>
        </div>
        <div class="container inpt">
          <input class="input" id="username" type="text" />
        </div>
      </div>
      <div class="container mb-3">
        <div class="label-p">
          <label for="password">Password </label>
        </div>
        <div class="row justify-content-center">
          <div class="col-10">
            <input class="input-pw" id="password" type="password" />
          </div>
          <button class="col-1 icn"><i class="bi bi-eye"></i></button>
        </div>
      </div>
      <div class="forget_pwd">
        <a href="#" class="lupa">Lupa Password?</a>
      </div>
      <button class="btn btn-success" type="submit">Login</button>

      <div class="cntr">
        <span class="text">atau masuk dengan</span>
      </div>

      <div class="social-media">
        <div class="btn-go">
          <div class="contentContainer">
            <i class="sc bi bi-google"></i>
          </div>
        </div>
        <div class="btn-fcb">
          <div class="contentContainer">
            <i class="sc bi bi-facebook"></i>
          </div>
        </div>
        <div class="btn-gh">
          <div class="contentContainer">
            <i class="sc bi bi-github"></i>
          </div>
        </div>
      </div>

      <div class="belum_punya_akun">
        <span class="buat"
          >Belum Memiliki Akun? <a href="#" class="daftar">Daftar</a></span
        >
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "LoginPage",
};
</script>
