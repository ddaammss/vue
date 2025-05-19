<template>
  <body class="login-page bg-body-secondary">
    <div class="login-box">
      <div class="login-logo">
        THE ONE KOREA
      </div>
      <div class="card">
        <div class="card-body login-card-body">
          <form action="../index3.html" method="post">
            <div class="input-group mb-3">
              <input type="email" class="form-control" placeholder="Email" />
              <div class="input-group-text"><span class="bi bi-envelope"></span></div>
            </div>
            <div class="input-group mb-3">
              <input type="password" class="form-control" placeholder="Password" />
              <div class="input-group-text"><span class="bi bi-lock-fill"></span></div>
            </div>
            <div class="row">
              <div class="col-8">
                <div class="form-check">
                  <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
                  <label class="form-check-label" for="flexCheckDefault"> Remember Me </label>
                </div>
              </div>
              <div class="col-4">
                <div class="d-grid gap-2">
                  <button type="submit" class="btn btn-primary">Sign In</button>
                </div>
              </div>
            </div>
          </form>
          <p class="mb-1"><a href="forgot-password.html">I forgot my password</a></p>
          <p class="mb-0">
            <a href="register.html" class="text-center"> Register a new membership </a>
          </p>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
export default {
  name: 'Login',
  // props: {
  //   msg: String
  // }
}
</script>
