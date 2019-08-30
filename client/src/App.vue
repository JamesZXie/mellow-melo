<template>
  <div id="app">
    <Header />
    <Menu />
    <Order />
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

*{
  padding: 0px;
  margin: 0px;
}

</style>
