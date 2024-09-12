<!-- 寫 JS 區塊 -->
<script setup>
// 可以import vue 元件
// import HelloWorld from './components/HellWorld.vue'

  import {ref} from 'vue';
  
  const num = ref(2);
  function clickMe(){
    num.value++
  }
</script>

<!-- html 的片段 -->
<template>
  <div>
    {{ num }}
    <button type="button" v-on:click="clickMe">點我+1</button>
  </div>
</template>


<!-- css 片段 -->
 <style csoped>
</style>