<template>
    <nav>
        <ul>
            <li v-for="navlogo in navLogoList" :key="navlogo">
                <a> {{navlogo}}</a>
            </li>
        </ul>
    </nav>
</template>

<script>
export default {
  name: "SystemHeader",
  data() {
    return {
      navLogoList: [1, 2, 3, 4]
    };
  }
};
</script>

<style scoped>
li {
  display: inline-block;
  background-color: black;
}
</style>
