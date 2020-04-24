<template>
  <div>
    <header>
      <Logo/>
    </header>
    <Navigation/>
    <nuxt/>
  </div>
</template>
<script>
  import "~/assets/app.css"
  import Logo from "~/components/Logo";
  import Navigation from "~/components/Navigation"

  export default {
    components: {
      Logo,
      Navigation
    }
  }
</script>
