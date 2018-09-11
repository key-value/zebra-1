<template>
  <main>
    <header></header>
    <aside></aside>
    <section></section>
    <footer></footer>
  </main>
</template>

<script>
export default {
  name: "BothSides",
  components: {},
  data() {
    return {
      counter: 0
    };
  }
};
</script>
<style scoped>
main {
  margin-left: auto;
  margin-right: auto;
  width: 960px;
}
header,
footer {
  margin: 10px 0;
  background: red;
  width: 960px;
  height: 30px;
  display: inline-block;
}
aside {
  float: left;
  width: 680px;
  height: 250px;
  color: #ffffff;
  background-color: #333333;
}
section {
  background: black;
  float: right;
  width: 270px;
  height: 250px;
  background-color: #999999;
}
</style>
