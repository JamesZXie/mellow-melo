<template>
  <div id="app">
    <Header />
    <div class="menu-order-container">
      <Menu />
      <Order />
    </div>
  </div>
</template>

<script>
import Header from "./components/cashier-view/Header"
import Menu from "./components/cashier-view/Menu"
import Order from "./components/cashier-view/Order"

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    Header,
    Menu,
    Order
  }
}
</script>

<style lang="scss">

#app {
  flex-direction: column;
  height: 100vh;
}

.menu-order-container {
  height: 100%;
  display: flex;
  flex-direction: row;
  background-color: black;
}

* {
  padding: 0px;
  margin: 0px;
}

</style>
