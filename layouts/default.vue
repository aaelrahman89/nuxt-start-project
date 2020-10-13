<template>
  <div>
    <Nuxt />
  </div>
</template>

<script>
export default {
    head(context) {
    return {
      htmlAttrs: {
        lang: this.$i18n.locale,
        dir: this.$i18n.locale == "ar" ? "rtl" : "ltr"
      }
    };
  }
}
</script>

<style scoped lang="scss">

</style>
