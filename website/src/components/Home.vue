<template>
  <div class="hello">
    <div class="menu">
      <div class="menu-item">
        <div class="menu-text">
          Resume
        </div>
      </div>
      <div class="menu-item">
        <div class="menu-text">
          Projects
        </div>
      </div>
      <div class="menu-item menu-center">
        Loveish Sarolia
      </div>
      <div class="menu-item">
        <div class="menu-text">
          Photography
        </div>
      </div>
      <div class="menu-item">
        <div class="menu-text">
          About
        </div>
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
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: calc(100vh - 60px);
  margin: 0.8%;
  /* filter: drop-shadow(0px 0px 7px rgba(150, 150, 150, 0.7)); */
}

.lettersize {
  width: 90%;
  padding: 0px
}

.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
}

.menu-item {
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu-text {
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  width: fit-content;
}

.menu-text:hover {
  color: #ffffff;
  border-bottom: 2px solid #ffffff;
}

.menu-center {
  font-size: 30px;
  font-weight: bold;
  color: #ffffff;
  cursor: pointer;
}
</style>
