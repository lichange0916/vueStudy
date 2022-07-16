<template>
    <div>
       <school></school>
       <student/>
    </div>
</template>

<script>
  // 引入组件
  import School from './School.vue'
  import Student from './Student.vue'

  export default {
      name:'app',
      components:{
        School,
        Student,
      }
  }
</script>