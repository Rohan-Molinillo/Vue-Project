<template>
  <header>
    <restaurant-row />
  </header>
</template>

<script>
import RestaurantRow from './components/RestaurantRow.vue'
export default {
  name: 'App',
  components: {
    RestaurantRow
  }
}
</script>

<style>
@import url('./style/reset.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto%3Awght%40300%3B400%3B700&display=swap');
#app {
  font-family: 'Roboto', sans-serif;
  padding: 20px;
}
</style>
