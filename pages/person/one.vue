<template>
    <div>
      <h1>
        person/one子路由
      </h1>
    </div>
</template>

<script>
    export default {
        name: "one",
        data(){
            return{
                title:'标题2'
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
