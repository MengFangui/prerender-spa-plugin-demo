<template>
  <div>
    <p @click="testMethod" class="p">
      test
    </p>
  </div>
</template>
<script>
export default {
  methods:{
    testMethod(){
      alert('test')
    }
  }
}
</script>
<style>
.p{
  cursor: pointer;
}
</style>


