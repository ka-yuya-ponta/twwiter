
<template>
  <div class="register">
  <Header/>
    <Nuxt/>
  </div>
</template>
<script>
export default {
   
    layout:'homes'
 
}
</script>
<style >





.register {
  background-color: black;
  width: 100%;
  height: 100vh;
  margin: 0;
  padding: 0;
}
h2 {
  font-size: 15px;
}
.content {
  background-color: white;
  width: 40%;
  margin:  100px auto;
  text-align: center; 
  border-radius: 5px;
  padding: 10px;
}
ul {
  padding: 0;
}
li {
  list-style: none;
}
input {
  color: gainsboro;
  border: 1px solid gainsboro;
  padding: 5px;
  border-radius: 3px;
}
button {
  width: 40%;
  border-radius: 10px;
  background-color: rgb(176, 18, 215);
  color: white;
  padding: 5px;
}
</style> 