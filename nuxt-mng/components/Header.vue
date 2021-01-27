<template>
  <header class="header">
    <ul class="nav-items">
      <li><nuxt-link to="/">Home</nuxt-link></li>
      <li><nuxt-link to="/users">Users</nuxt-link></li>
      <li><nuxt-link to="/products">Products</nuxt-link></li>
    </ul>
  </header>
</template>

<style>
  .header {
    display: flex;
    justify-content: space-around;
    flex-basis: 100%;
  }
  .nav-items {
    display: flex;
    justify-content: space-around;
    list-style: none;
    flex-basis: 100%;
  }
</style>
