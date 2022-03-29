<template>
  <main id="homepage">
    <div class="main-title">
      <span class="main-title_small">Hi! My name is</span>
      <span class="main-title_large">J. Gabriel Onofre</span>
    </div>
    <div class="lead">
      I'm a full-stack software developer focused on creating clean,
      creative and user-friendly applications.
    </div>
  </main>
</template>

<script>
export default {
  name: 'IndexPage',
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    }
  }
}
</script>

<style scoped>

</style>
