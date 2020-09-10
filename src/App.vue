<template>
  <div id="app">
    <center>
    <input v-model="msg" placeholder="write here..."><br>
    <div class = "cap"> {{ msg }}</div>
    </center>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    
  },
//=================
  data(){
    return{
      msg: ''
    }
  }

//==============

  //data(){
    //return{
      //msg: 'Hello'
    //}
  //}
}

</script>

<style>
body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
  position: fixed;
  top: 50%;
  left: 50%;
  margin-top: -50px;
  margin-left: -100px;
}
div.cap {
  text-transform: uppercase;
}
</style>
