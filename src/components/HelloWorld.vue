<template>
  <div class="hello">
    <h1>"La mia prima app con Vue CLI!"</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
template {
  background-color: cyan;
}
h1 {
  margin: 40px 0 0;
  color: coral;
  background-color: cyan;
}
</style>
