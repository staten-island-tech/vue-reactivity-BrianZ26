<script setup>
const toppings = [
  {
    name: 'Pepperoni',
    img: 'https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/pepperoni.png'
  },
  {
    name: 'Sausage',
    img: 'https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/beef.png'
  },
  {
    name: 'Mushrooms',
    img: 'https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/mushrooms.png'
  },
  {
    name: 'Chicken',
    img: 'https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/chicken.png'
  },
  {
    name: 'Bacon',
    img: 'https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/bacon.png'
  },
  {
    name: 'Cheese',
    img: 'https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/cheese.png'
  }
]
</script>

<template>
  <div v-for="topping in toppings" class="select">
    <h2 class="selector-text">{{ topping.name }}</h2>
    <img :src="topping.img" class="img" />
  </div>
</template>

<style scoped>
.select {
  flex-direction: column;
  flex-wrap: wrap;
  border: 5px solid rgb(0, 0, 0);
  padding: 20px;
  margin: 20px;
  width: 200px;
}
.selector-text {
  text-align: center;
}
.img {
  max-width: 130%;
}
</style>
