<template>
  <div class="footpage container">
    <div class="footpage_info">
      <div class="footpage_infotext">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur
        error sapiente minima totam atque quas, tempora neque quam porro sed
        ratione, recusandae animi eum eaque labore. Animi quod quasi optio.
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laborum
        aperiam quis, nobis dolore eveniet, earum error, delectus neque nihil
        nemo enim reiciendis libero qui quisquam. Voluptates voluptate possimus
        culpa necessitatibus!
      </div>
    </div>
    <div class="footpage_icon">
      <a href=""><i class="bx bxl-facebook-square"></i></a>
      <a href=""><i class="bx bxl-youtube"></i></a>
      <a href=""><i class="bx bxl-twitter"></i></a>
    </div>
  </div>
</template>

<script>
export default {
  name: "footpage",
};
</script>

<style scoped>
.footpage {
  margin-top: 30vh;
  height: 40vh;
  background-color: rgb(97, 235, 143);
  box-shadow: 3px 3px 3px 2px rgba(0, 0, 0, 0.2);
  bottom: 0;
}
.footpage_info {
  width: 80%;
  height: 80%;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.footpage_icon {
  width: 100%;
  height: 20%;
  font-size: 40px;
  display: flex;
  justify-content: flex-end;
}
.footpage_icon a {
  padding-right: 20px;
}
</style>
