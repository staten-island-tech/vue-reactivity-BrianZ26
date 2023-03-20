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
    <h1 class="selector-text">{{ topping.name }}</h1>
    <img :src="topping.img" />
  </div>
</template>
<!-- https://212newyorkpizza.com/wp-content/plugins/pizzatime/images/tomato-sauce.png -->
<!-- https://212newyorkpizza.com/wp-content/uploads/2019/01/pizza-crust.png -->
<style scoped>
.selector-text {
  text-align: center;
}
.select {
  align-content: center;
  flex-direction: column;
  flex-wrap: wrap;
  border: 5px solid rgb(0, 0, 0);
  padding: 20px;
  margin: 20px;
}
</style>
