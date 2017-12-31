<template>
   <div>
    {{info}}
   <button @click="demo">click demo</button>
   </div>
</template>
<script>
import dalong from "./app";
 export default {
  data(){
   return {
    info:dalong.demo()
   }
 },
 methods:{
   demo(){
    alert(dalong.demo())
   }
 }
 }
</script>