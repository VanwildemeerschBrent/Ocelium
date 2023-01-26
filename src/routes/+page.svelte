<script>
  import "../app.css";
  import Logo from "$lib/assets/logo.svg";
  import Bg from "$lib/assets/bg.jpg";
</script>

<div class="container">
  <img src={Bg} class="bg" alt="background" />
  <img src={Logo} class="logo" alt="logo" />
</div>

<style>
  .container {
    width: 100vw;
    height: 100vh;
    overflow: hidden;
    position: relative;
  }
  .bg {
    position: absolute;
    width: 100vw;
    height: 100vh;
    background-size: cover;
  }
  .logo {
    position: relative;
    display: block;
    width: 30%;
    margin: auto;
    transform: translateY(-50%);
    top: 50%;
  }

  @media only screen and (max-width: 600px) {
    .logo {
      width: 70%;
    }
  }
</style>
