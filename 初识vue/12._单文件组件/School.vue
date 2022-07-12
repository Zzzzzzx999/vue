<template>
    <div class="demo">
        <h2>学校名称：{{Name}}</h2>
        <h2>学校地址：{{adress}}</h2>
        <button @click="showName">点我显示学校名称</button>
    </div>
</template>
<script>
    export default({
        name:'School',
        data() {
            return {
                Name:'厦门工学院',
                address:'厦门'
            }
        },
        methods: {
            ShowName(){
                alert(this.Name)
            }
        },
    })
</script>
<style>
    .demo{
        background-color: aqua;
    }
</style>