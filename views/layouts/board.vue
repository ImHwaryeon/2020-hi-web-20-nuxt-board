<template lang="pug">
  div.container-wrapper
    header.header-wrapper
      h1 Header
    Nuxt.nuxt-wrapper
    footer.footer-wrapper
      p copyright hwaryeon
</template>
<script>
export default {
  
}
</script>
<style lang="scss">
  .container-wrapper {
    height: 100vh;
    @include flex($FS, $ST);
    flex-direction: column;
    .header-wrapper {
      background-color: $colorLight;
      color: $colorBlack;
    }
    .nuxt-wrapper {
      flex-grow: 1;
    }
    .footer-wrapper {
      background-color: $colorLight;
      color: $colorBlack;
    }
  }
</style>