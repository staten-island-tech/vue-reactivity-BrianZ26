<script setup>
import toppings from '../src/components/ToppingSelector.vue'
import create from '../src/components/PizzaMain.vue'
</script>

<template>
  <div class="website">
    <div class="page-header">
      <h1>Test</h1>
    </div>
    <div class="display">
      <toppings></toppings>
    </div>
    <div>
      <create></create>
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
</style>
