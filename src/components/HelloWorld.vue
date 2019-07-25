<template>
  <div class="hello"> 
      <button @click="showFn"> 点击</button>
  </div>
</template>

<script>
import Vue from 'vue'
// import toastTest from '../plugin'
// Vue.use(toastTest) 
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }, 
  methods:{
    showFn(){
       this.$toast('嗨，欢迎一起来学习')
    }
  }
}
</script>
 
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
