<template>
  <div class="blog-content" v-html="content" />
</template>

<script>
export default {
  props: {
    content: String
  }
};
</script>

<style lang="stylus" scoped>
p
  font-size 1.15rem
  line-height 1.5
h2
  font-size 2rem
h3
  font-size 1.5rem
h4, h5, h6
  font-size 1.15rem
</style>
