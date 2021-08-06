<template>
  <div class="nav container">
    <div class="logo">
      <img alt="Vue logo" src="@/assets/logo.png" />
    </div>
    <ol class="nav_ol">
      <a href=""><li class="nav_item">Home</li></a>
      <a href="item.vue#item"><li class="nav_item">Item</li></a>
      <a href="context.vue#context"><li class="nav_item">Content</li></a>
    </ol>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.logo {
  display: flex;
  width: 50%;
  align-items: center;
  justify-items: flex-start;
}
.logo img {
  width: 50px;
  height: 50px;
}

.nav {
  height: 15vh;
  top: 0;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  border-radius: 5px;
}
.nav_ol {
  display: flex;
  align-items: center;
  justify-content: space-around;
  width: 50%;
}
.nav_item {
  font-size: 1.2rem;
  font-weight: 400;
}
</style>
