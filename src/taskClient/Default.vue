<template >
  <main class="contain">

    <header></header>

    <aside class="sidebar">
      <ul>
        <li>1111</li>
        <li>2222</li>
        <li>3333</li>
        <li>4444</li>
      </ul>
    </aside>
    <section class="mainSection">
      <!-- <nav class="navbar orangered">2</nav> -->
      <!-- <section class="content yellow">5
                <article class="blue">4</article>
            </section> -->
    </section>
    <footer class="green">6</footer>
  </main>
</template>

<script>
export default {
  name: "Main",
  components: {},
  data() {
    return {
      counter: 0
    };
  }
};
</script>
<style scoped>
* {
  margin: 0px;
  padding: 0px;
}
.contain {
  background-color: #555;
  height: 100%;
  display: block;
}
header {
  height: 60px;
  width: 100%;
  background-color: darkslateblue;
  margin-bottom: 12px;
}
.sidebar {
  border-color: blueviolet;
  border-width: 1px;
  border-style: double;
  margin-left: 10px;
  margin-bottom: 10px;
  width: 250px;
  height: 100%;
  padding: 20px 30px;
}
.sidebar ul {
  list-style: none;
  line-height: 30px;
}
.mainSection {
  width: 100px;
  height: 10px;
}
footer {
  background-color: darkslateblue;
  width: 100%;
  height: 30px;
  position: absolute;
  bottom: 3px;
}
</style>
