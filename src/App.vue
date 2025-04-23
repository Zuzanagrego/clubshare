<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
<header class="header">
  <ul>
    <li>Inventory</li>
    <li>Messages</li>
    <li>My Stuff</li>
  </ul>
</header>

<main>
  <ul>
    <li>Borrow</li>
    <li>Rent</li>
    <li>Buy</li>
  </ul>

  <div class="filter">
    Filter
  </div>

  <div class="item-list-body">
    <ul>
      <li>
        <div class="item-list-item">
          <img/>
          <h1>Item 1</h1>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate, quas!</p>
        </div>
      </li>
      <li>
        <div class="item-list-item">
          <img/>
          <h1>Item 2</h1>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate, quas!</p>
        </div>
      </li>
      <li>
        <div class="item-list-item">
          <img/>
          <h1>Item 3</h1>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate, quas!</p>
        </div>
      </li>
      <li>
        <div class="item-list-item">
          <img/>
          <h1>Item 4</h1>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate, quas!</p>
        </div>
      </li>
      <li>
        <div class="item-list-item">
          <img/>
          <h1>Item 5</h1>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate, quas!</p>
        </div>
      </li>
      <li>
        <div class="item-list-item">
          <img/>
          <h1>Item 6</h1>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate, quas!</p>
        </div>
      </li>
    </ul>
  </div>
</main>
  
</template>

<style scoped>

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
