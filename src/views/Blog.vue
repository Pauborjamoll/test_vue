<template>
    <Blog/>
    <Footer/>
</template>
<script>

import Blog from '@/components/bodyBlog.vue'
import Footer from '@/components/footer_component.vue'
export default {
  name: 'BlogView',

  components: {
    Blog ,
    Footer
  }
}
</script>