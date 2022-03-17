<template>
  <div class="blog-layout">
    <NavigationBar isBlog="true" />
    <Nuxt />
    <BlogFooter />
  </div>
</template>

<script>
import NavigationBar from '@/components/GeneralLayout/NavigationBar.vue'
import BlogFooter from '@/components/GeneralLayout/BlogFooter.vue'

export default {
  name: 'BlogLayout',

  components: {
    NavigationBar,
    BlogFooter
  },

  data() {
    return {
    }
  },
}
</script>
