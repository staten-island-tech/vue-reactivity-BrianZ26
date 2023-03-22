<script setup>
import toppings from '../src/components/ToppingSelector.vue'
</script>

<template>
  <div class="website">
    <div class="page-header">
      <h1>Test</h1>
      <div class="create">
        <img
          src="https://212newyorkpizza.com/wp-content/uploads/2019/01/pizza-crust.png"
          class="main"
        />
        <img
          src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/tomato-sauce.png"
          class="main"
        />
        <img
          src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/cheese.png"
          class="main"
        />
        <img
          src="https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/pepperoni.png"
          class="main"
        />
      </div>
    </div>
  </div>
</template>
<style scoped>
h1 {
  text-align: center;
}
.website {
  display: flex;
  flex-direction: column;
}
.display {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.main {
  position: absolute;
  top: 25%;
  width: 100%;
  width: 500px;
  align-content: center;
}
</style>
