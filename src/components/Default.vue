<template >
  <div class="contain">
    <aside class="sidebar Red">
      3
      <br> 43
    </aside>
    <section class="mainSection">
      <system-header class="navbar"></system-header>
      <!-- <nav class="navbar orangered">2</nav> -->
      <!-- <section class="content yellow">5
                <article class="blue">4</article>
            </section> -->
      <footer class="green">6</footer>
    </section>
  </div>
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
  height: 80px;
  padding: 30px;
}

.mainSection {
  padding-bottom: 0;
  position: relative;
  float: right;
  width: calc(100% - 250px);
  right: 0px;
  display: inline-block;
}

.sidebar {
  display: inline-block;
  top: 0px;
  /* min-height: 100vh; */
  width: 250px;
}
.content {
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
