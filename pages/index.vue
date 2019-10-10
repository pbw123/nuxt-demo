<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        nuxtDemo
      </h1>
      <h2 class="subtitle">
        My stupendous Nuxt.js project
        {{title}}
      </h2>

    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import axios from 'axios'

export default {
  components: {
    Logo
  },
    data(){
      return{
          title:'title67889'
      }
    },
    async asyncData () {
        let { data } = await axios.get(`https://api.apiopen.top/searchPoetry?name=古风二首%20二`)
        return { title: data.result }
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

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
