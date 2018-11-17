<template lang="html">
  <div class="sample">
    <div>
      <slot/>
    </div>
    <div class="blue">
      <slot name="named"/>
    </div>
    <nuxt-link to="/about">ABOUT</nuxt-link>
  </div>
</template>
​
<script>
export default {
  props: {
    title: {
      type: String,
      default: 'Defalut Title'
    }
  },
  data() {
    return {
      name: 'shin'
    }
  }
}
</script>
​
<style lang="scss" scoped>
.hide {
  display: none;
  &.seven {
    display: block;
  }
}
</style>
