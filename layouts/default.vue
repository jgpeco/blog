<template>
  <div class="default-layout">
    <NavigationBar />
    <Nuxt />
    <DefaultFooter />
  </div>
</template>

<script>
import NavigationBar from '@/components/GeneralLayout/NavigationBar.vue'
import DefaultFooter from '@/components/GeneralLayout/DefaultFooter.vue'

export default {
  name: 'DefaultLayout',

  components: {
    NavigationBar,
    DefaultFooter
  },

  data() {
    return {
    }
  },
}
</script>
