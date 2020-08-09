<template>
  <div class="hello">
    <div class="menu">
      <div class="menu-item menu-text">
        Resume
      </div>
      <div class="menu-item menu-text">
        Projects
      </div>
      <div class="menu-item menu-center">
        Loveish Sarolia
      </div>
      <div class="menu-item menu-text">
        Photography
      </div>
      <div class="menu-item menu-text">
        About
      </div>
    </div>
    <div class="name">
      <img src="../assets/logotransparent.png" class="lettersize">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.name {
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: 100vh;
  margin: 0.8% 
}

.lettersize {
  width: 90%;
  vertical-align: top;
}

.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
}

.menu-item {
  flex: 1;
  text-align: center;
  font-size: 20px;
  color: #707070
}

.menu-text {
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #707070;
  width: fit-content;
}

.menu-text:hover {
  border-bottom: 2px solid #ffffff;
}

.menu-center {
  font-size: 30px;
  color: #EAEAEA;
}
</style>
