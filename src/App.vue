<template>
    <div>
        <!--<input type="button" value="点我试试"
        @click="sayHi">-->
<!--        头部组件-->
    <top></top>
    </div>
</template>

<script>
    import top from 'src/components/01.top'
    export default {
        //注册组件
        components:{
          top//top:top
        },
        methods:{
            sayHi(){
                alert("我出现了！！！")
            }
        }
    }
</script>

<style scoped>

</style>