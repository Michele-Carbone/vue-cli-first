<template>
  <div id="jumbotron">
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
h3 {
  color: chocolate;
}

#jumbotron {
  background-color: darkgreen;
}
</style>
