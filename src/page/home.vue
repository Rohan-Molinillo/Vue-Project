<template>
  <div class="home">
    <RestaurantRow />
  </div>
</template>

<script>
//IMPORT
import BDD from '../BDD.js'

//COMPONENTS
import RestaurantRow from '../components/RestaurantRow.vue'
export default {
  name: 'HomeItem',
  components: {
    RestaurantRow
  },
  setup() {
    class Restaurant {
      constructor(name, note, image, drive_time) {
        this.name = name
        this.note = note
        this.image = image
        this.drive_time = drive_time
      }
    }

    const resto = new Restaurant('Mcdo', 4.8, 'img', '45min')
  }
}
</script>

<style lang="scss"></style>
