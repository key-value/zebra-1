<template >
    <section>
        <aside class="sidebar Red">3
        </aside>
        <section>
            <nav class="navbar orangered">2</nav>
            <section class="content yellow">5
                <article class="blue">4</article>
            </section>
            <footer class="green">6</footer>
        </section>
    </section>
</template>

<script>
import SystemHeader from "./System/SystemHeader";

export default {
  name: "Main",
  components: {
    SystemHeader
  },
  data() {
    return {
      counter: 0
    };
  }
};
</script>

<style scopedSlots>
.navbar {
  position: relative;
  height: 3rem;
  width: calc(100% - 250px);
  right: 0%;
  padding: 30px;
}
.sidebar {
  position: fixed;
  top: 0px;
  height: 100vh;
  width: 250px;
}
.content {
  display: inline-block;
  position: relative;
}
.Red {
  background: red;
}
.black {
  background: black;
}
.blue {
  background: blue;
}
.yellow {
  background: yellow;
}
.green {
  background: green;
}
.orangered {
  background: orangered;
}
</style>
