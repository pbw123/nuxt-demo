<template>
    <div>
      <img :src="img" alt="">
      <nuxt-link to="/user">用户index</nuxt-link>
      <nuxt-link to="/user/one">子路由one</nuxt-link>
      <nuxt-child/>
    </div>
</template>

<script>
    const img = require('../static/img5.png');
    export default {
        name: "user",
        data(){
            return{
                img:img
            }
        }
    }
</script>

<style scoped>

</style>
