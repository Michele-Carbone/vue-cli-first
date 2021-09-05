<template>
  <div>
    <h3>Section One</h3>
  </div>
</template>

<script>
export default {
  name: "Jumbotron",
  props: {
    msg: String,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h3 {
  color: chocolate;
}
</style>
