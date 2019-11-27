<template>
  <nuxt-link to="/">
    testOne
  </nuxt-link>
</template>

<script>
export default {
  head () {
    return {
      title: this.title,
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        { property: 'og:title', content: '逢甲商圈逢甲商圈逢甲商圈逢甲商圈逢甲商圈' }
      ]
    }
  }
}
</script>
