<template>
  <main>
    <header></header>
    <aside></aside>
    <section>
      section<br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br> asddddddddddd
      <br>
    </section>
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
header {
  margin: 10px 0;
  background: red;
  width: 100%;
  height: 30px;
  display: inline-block;
}
footer {
  position: absolute;
  bottom: 10px;
  left: auto;
  right: auto;
  background: red;
  height: 30px;
  width: 960px;
}
aside {
  display: block;
  float: left;
  height: 250px;
  width: 30%;
  color: #ffffff;
  background-color: #333333;
}
section {
  background: black;
  float: right;
  width: 70%;
  background-color: #999999;
}
</style>
