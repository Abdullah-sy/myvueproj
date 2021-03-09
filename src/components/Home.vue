<template>
  <div class="hello">
    <div class="menu">
        <div class="menu-item menu-text">
          Resume
        </div>
        <div class="menu-item menu-text">
          Skating
        </div>
        <div class="menu-item menu-center">
          Abdullah
        </div>
        <div class="menu-item menu-text">
          Youtube
        </div>
        <div class="menu-item menu-text">
          About
        </div>
        </div>
        <div class="name">
      <div class="letter"><img src="../../img/A.png" class="letterh"></div>
      <div class="letter"><img src="../../img/B.png" class="letterh"></div>
      <div class="letter"><img src="../../img/A.png" class="letterh"></div>
      <div class="letter"><img src="../../img/B.png" class="letterh"></div>
      <div class="letter"><img src="../../img/A.png" class="letterh"></div>
      <div class="letter"><img src="../../img/B.png" class="letterh"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HellWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.name {
  display: flex;
  /*border: 1px solid red;*/
  align-items: center;
  justify-content: center;
  vertical-align:middle ;
  font-size: 70px;
  width: 100vw;
  height: 60vw;
}
.letter {
  margin: 20px;
  filter: drop-shadow(0px 0px 7px rgba(240, 21, 156, 0.7));
}
.letterh{
  width: 100%;

}
.menu{
  display:flex;
  align-items: center;
  justify-content: space-between;
}
.menu-item{
  flex: 1;
  /*border: 1px solid red;*/
  text-align: center;
  color: #707070;
}
.menu-center{
  font-size: 36px;
  color: #ddd ;
}
.menu-text{
  font-size: 20px;
  color: #818181 ;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
}
.menu-text:hover{
  font-size: 36px;
  border-bottom: 2px solid #c278ff;
}
</style>
