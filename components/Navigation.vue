<template>
  <nav>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/contact">Contact</nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
nav li {
  display: inline-block;
}
nav a {
  text-decoration: none;
}
</style>