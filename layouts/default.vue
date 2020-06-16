<template>
  <div class="landing-page">
    <NavBar></NavBar>
    <nuxt />
  </div>
</template>

<script>
  import Navbar from "../components/Navbar/Navbar";

  export default {
    components:{
      'NavBar': Navbar
    }
  }
</script>
