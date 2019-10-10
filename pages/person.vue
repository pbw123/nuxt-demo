<template>
    <div>
      <nuxt-link to="/person">子路由index</nuxt-link>
      <nuxt-link to="person/one">子路由one</nuxt-link>
      <nuxt/>
    </div>
</template>

<script>
    export default {
        name: "person"
    }
</script>

<style scoped>

</style>
