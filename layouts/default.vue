<template>
  <div>
    <nuxt-link to="/">首页</nuxt-link>
    <nuxt-link to="/user">用户index</nuxt-link>

    <nuxt-link to="/users/java">动态路由2</nuxt-link>
    <nuxt-link to="/person">路由嵌套</nuxt-link>


    <nuxt />
  </div>
</template>

<style >
  /*.active-link{*/
  /*  background: orangered;*/
  /*}*/

  .exact-active-link{
    background: orange;
  }
</style>
