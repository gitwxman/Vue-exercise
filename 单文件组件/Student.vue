<template>
    <div>
        <h1>学生信息：{{name}}</h1>
        <h1>学生住址：{{site}}</h1>
    </div>
</template>

<script>
export default {
    name:"Student",
    data(){
        return {
            name:"迪丽热巴",
            site:"辽宁抚顺"
        }
    }
}
</script>

<style>

</style>