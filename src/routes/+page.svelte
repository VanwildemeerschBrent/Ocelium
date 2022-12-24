<script>
  import "../app.css";
  import Logo from '$lib/assets/logo.svg';
  import Bg from '$lib/assets/bg.jpg';
</script>

<div class="w-screen h-screen relative">
  <img src={Bg} class="absolute w-screen h-screen left-0 top-0 opacity-75" alt="background"/>
  <img src={Logo} class="m-auto w-1/3 logo" alt="logo"/>
</div>

<style>
  .logo{
    position: relative;
    transform: translateY(-50%);
    top: 50%;
  }
</style>