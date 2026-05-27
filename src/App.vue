<!--
 * @Descripttion: 
 * @Author: guohongtao12@jd.com
 * @Date: 2026-05-27 10:35:34
 * @LastEditors: guohongtao12@jd.com
 * @LastEditTime: 2026-05-27 14:56:01
 * @FilePath: /player/src/App.vue
-->
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
                console.log(11111)
                console.log('自定义文档111133333')
                console.log('自定义文档111122222')
            },
            sayHi111(){
                alert("修复bug")
            },
            sayHi111(){
                alert("修复bug2")
            },
            sayHi1113(){
                alert("修复bug4")
            }
        }
    }
</script>

<style scoped>

</style>