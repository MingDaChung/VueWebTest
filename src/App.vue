<template>
  <div id="app">
    <HelloWorld />
    <test />
    <item />
    <context />
    <footpage />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import test from "./components/test.vue";
import item from "./components/item.vue";
import context from "./components/context.vue";
import footpage from "./components/footpage.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    test,
    item,
    context,
    footpage,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;400;500&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  scroll-behavior: smooth;
}
.container {
  width: 90%;
  margin: 0 auto;
}
a {
  text-decoration: none;
}
a:visited {
  color: black;
}
a:hover {
  font-size: 1.5rem;
  color: rgb(33, 192, 139);
  transition: 0.3s;
}
li {
  list-style: none;
}
</style>
