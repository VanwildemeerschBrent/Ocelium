<script>
  import "../app.css";
  import Logo from '$lib/assets/logo.svg'
</script>

<div class="w-screen h-screen relative">
  <img src={Logo} class="m-auto w-1/2 logo" alt="logo"/>
</div>

<style>
  .logo{
    position: relative;
    transform: translateY(-50%);
    top: 50%;
  }
</style>