<template>
  <div>
    <h1>学校名称：{{name}}</h1>
    <h1>学校地址：{{site}}</h1>
    <button @click="show">点击显示学校名称</button>
  </div>
</template>

<script>
export default {
    name:"School",
    data(){
        return{
            name:"尚硅谷",
            site:"北京昌平"
        }
    },
    methods:{
        show(){
            alert(this.name)
        }
    }
}
</script>

<style>

</style>