<template>
    <div>
      <nuxt-link to="/person">子路由index</nuxt-link>
      <nuxt-link to="person/one">子路由one</nuxt-link>
<!--      <nuxt-link to="person/">动态路由嵌套子路由category</nuxt-link>-->
<!--      <nuxt-link to="person/">动态路由嵌套子路由student</nuxt-link>-->

      <nuxt/>
    </div>
</template>

<script>
    export default {
        name: "person",
        layout:'blog'

    }
</script>

<style scoped>

</style>
