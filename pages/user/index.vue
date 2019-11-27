<template>
  <div class="container">
    <nuxt-link to="/user/one">
      test
    </nuxt-link>
  </div>
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

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
