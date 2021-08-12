<template>

  <div>
    <section class="side">
      <h1>SHARE</h1>
      <p><span class="material-icons">home</span>ホーム</p>
      <p><span class="material-icons">logout</span>ログアウト</p>
      <p>シェア</p>
      <textarea name="" id="" cols="30" rows="10"> </textarea>
      <button>シェアする</button>
    </section>
  </div>
</template>
<script>

export default {
  head: {
    link: [
      { rel: 'stylesheet', href: 'https://fonts.googleapis.com/icon?family=Material+Icons' }
    ]
  }
}
      </script>
<style scoped>
.side {
  color: white;
  background: black;
  width: 100%;
}
p {
  align-items: center
}
span {
  position: relative;
  top: 5px;
  margin-right: 10px;
 
}
textarea {
  background: black;
  border: 1px solid gainsboro ;
  width: 100%;
  color: white;
}
button {
  width: 100px;
  display: block;
  float: right;

}

</style> 
