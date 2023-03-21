<script setup>
import toppings from '../src/components/ToppingSelector.vue'
</script>

<template>
  <div class="website">
    <div class="page-header">
      <h1>Test</h1>
    </div>
    <div class="create">
      <img
        src="https://212newyorkpizza.com/wp-content/uploads/2019/01/pizza-crust.png"
        class="main"
      />
    </div>
    <div class="display"><toppings></toppings></div>
  </div>
</template>
<!-- https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/tomato-sauce.png -->
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
</style>
