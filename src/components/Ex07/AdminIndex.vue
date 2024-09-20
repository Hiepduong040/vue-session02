<template>
  <div>
    <h1>Ex07</h1>
    <div class="admin">
      <Header />
      <Menu />
      <Main />
      <Footer />
    </div>
  </div>
</template>
  
  <script setup>
import Header from "./Header.vue";
import Menu from "./Menu.vue";
import Main from "./Main.vue";
import Footer from "./Footer.vue";
</script>
  
  <style scoped>
.admin {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.header,
.footer {
  width: 100%;
}

.menu {
  width: 200px;
  float: left;
}

.main {
  flex-grow: 1;
  margin-left: 200px;
}

.footer {
  margin-top: auto;
}
</style>
  