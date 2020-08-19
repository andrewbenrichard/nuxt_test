<template>
  <header class="header">
    <h1 class="title">Test</h1>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/c/test1">Test1</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/c/test2">Test2</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "AppHeader"
};
</script>

<style>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px dotted #ccc;
}

.header .title {
  font-size: 3rem;
  color: #fff;
}

.header ul {
  display: flex;
}

.header a {
    display: inline-block;
    background: #fff;
    color: #333;
    padding: 0.3rem 1rem;
    border-radius: 45px;
    margin-right: 0.5rem;
}
</style>
