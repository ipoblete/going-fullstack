<template>
  <div id="app">
    <header>
      <img alt="Vue logo" src="./assets/logo.png">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/superheroes">Superheroes</RouterLink>
      </nav>
    </header>

    <main>
      <RouterView></RouterView>
    </main>

  </div>
</template>

<script>
export default {};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
