<template>
    <div>
        <h1>学生名字：{{name}}</h1>
        <h1>学生年龄：{{age}}</h1>
    </div>
</template>

<script>
export default {
    name:"Student",
    data(){
        return {
            name:"迪丽热巴",
            age:24
        }
    }
}
</script>

<style>

</style>