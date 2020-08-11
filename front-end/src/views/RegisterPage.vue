<template>
  <div class="container">
    <div class="row justify-content-center">
      <div class="register-form">
        <div class="logo-wrapper">
          <img class="logo" src="/static/images/logo.png">
          <div class="tagline">Open source task management tool</div>
        </div>
        <form>
          <div class="form-group">
            <input type="text" class="form-control" id="username">
          </div>
          <div class="form-group">
            <input type="text" class="form-control" id="emailAddress">
          </div>
          <div class="form-group">
            <input type="text" class="form-control" id="password">
          </div>
          <button type="submit" class="btn btn-primary btn-block">Create account</button>
        </form>
      </div>
    </div>

    <footer class="footer">
      <span class="copyright">@2020 TaskAgile.com</span>
      <ul class="footer-links list-inline float-right">
        <li>About</li>
        <li>About</li>
        <li>About</li>
        <li>About</li>
      </ul>
    </footer>
  </div>
</template>

<script>
  export default {
    name: 'RegisterPage'
  }
</script>

<style lang="scss" scoped>
  .container {max-width: 900px;}
  .register-form {margin-top: 50px; max-width: 320px;}
  .logo-wrapper {margin-bottom: 40px;}
  .footer {width: 100%; line-height: 40px; margin-top: 50px;}
</style>
