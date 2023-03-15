<script setup>
const toppings = [
  { name: 'Pepperoni', img: 'https://trottospizza.com/wp-content/uploads/2017/12/pepperoni.png' },
  {
    name: 'Sausage',
    img: 'https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/beef.png'
  },
  {
    name: 'Mushrooms',
    img: 'https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/mushrooms.png'
  },
  { name: 'Bacon' },
  { name: 'Onions' },
  { name: 'Peppers' },
  { name: 'Chicken' }
]
console.log(toppings)
</script>

<template>
  <li v-for="topping in toppings">
    {{ topping.name }}
  </li>
</template>

<style scoped></style>
