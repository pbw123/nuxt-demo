<template>
    <div>
      <nuxt-link to="/user">用户index</nuxt-link>
      <nuxt-link to="/user/one">子路由one</nuxt-link>
      <nuxt-child/>
    </div>
</template>

<script>
    export default {
        name: "user"
    }
</script>

<style scoped>

</style>
