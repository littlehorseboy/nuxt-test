<template>
  <nuxt-link to="/user/one">
    test
  </nuxt-link>
</template>

<script>
export default {
  head () {
    return {
      title: this.title,
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        { property: 'og:title', content: '一中商圈一中商圈一中商圈一中商圈一中商圈一中商圈' }
      ]
    }
  }
}
</script>
