<script setup>
import { cheese } from './store'
import { pepperoni } from './store'
import { mushrooms } from './store'
import { chicken } from './store'
import { bacon } from './store'
import { beef } from './store'
</script>
<template>
  <div class="create">
    <img
      src="https://212newyorkpizza.com/wp-content/uploads/2019/01/pizza-crust.png"
      class="main"
      draggable="false"
    />
    <img
      src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/tomato-sauce.png"
      class="main"
      draggable="false"
    />
    <img
      v-if="cheese"
      src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/cheese.png"
      class="main"
      draggable="false"
    />
    <img
      v-if="pepperoni"
      src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/pepperoni.png"
      class="main"
      draggable="false"
    />
    <img
      v-if="mushrooms"
      src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/mushrooms.png"
      class="main"
      draggable="false"
    />
    <img
      v-if="chicken"
      src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/chicken.png"
      class="main"
      draggable="false"
    />
    <img
      v-if="bacon"
      src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/bacon.png"
      class="main"
      draggable="false"
    />
    <img
      v-if="beef"
      src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/beef.png"
      class="main"
      draggable="false"
    />
  </div>
</template>
<style scoped>
.main {
  position: absolute;
  align-content: center;
  left: 100%;
}
.create {
  width: 25%;
}
h1 {
  align-self: center;
}
</style>
