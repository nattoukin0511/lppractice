<template>
  <div id="app">
    <p>{{people.boy}}</p>
    <p>{{people.girl}}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      people: {
        boy: "男の子",
        girl: "女の子"
      }
    };
  }
};
</script>

<style></style>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: red;
  margin-top: 60px;
}
</style>
