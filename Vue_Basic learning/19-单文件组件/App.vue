<template>
<div>
<school></school>
<student></student>
 </div> 
</template>

<script>
// 引入组件
import scool from './school.vue'
import student from "./student.vue"
export default {
 name:'App',
 components:{
   school,
   student
 }
}
</script>

<style>

</style>