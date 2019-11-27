<template>
  <div class="container">
    <nuxt-link to="/user">
      user
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
        { property: 'og:title', content: '商圈圈圈圈圈' }
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
