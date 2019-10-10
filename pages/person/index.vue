<template>
    <div>
      <h1>
        person/index子路由
      </h1>
    </div>
</template>

<script>
    export default {
        name: "index",
        data(){
            return{
                title:'标题1'
            }
        },
        head(){
            return{
                title: this.title
            }
        }
    }
</script>

<style scoped>

</style>
