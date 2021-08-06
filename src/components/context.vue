<template
  ><div class="context_boxmulti" id="context">
    <div class="context_box container">
      <div class="context_img">
        <img alt="Vue logo" src="@/assets/logo.png" />
      </div>
      <div class="context_textbox">
        <div class="context_text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur
          quisquam modi unde mollitia animi minima rerum inventore quaerat ab
          earum, tempore ex iure eos pariatur incidunt accusantium atque
          similique esse. Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Molestias, iste neque nemo placeat impedit non. Ad, a. Minima
          consequatur, corrupti numquam, nam laboriosam atque reprehenderit,
          vitae tempore ad laudantium a?
        </div>
      </div>
    </div>
    <div class="context_box container">
      <div class="context_img">
        <img alt="Vue logo" src="@/assets/logo.png" />
      </div>
      <div class="context_textbox">
        <div class="context_text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur
          quisquam modi unde mollitia animi minima rerum inventore quaerat ab
          earum, tempore ex iure eos pariatur incidunt accusantium atque
          similique esse. Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Molestias, iste neque nemo placeat impedit non. Ad, a. Minima
          consequatur, corrupti numquam, nam laboriosam atque reprehenderit,
          vitae tempore ad laudantium a?
        </div>
      </div>
    </div>
    <div class="context_box container">
      <div class="context_img">
        <img alt="Vue logo" src="@/assets/logo.png" />
      </div>
      <div class="context_textbox">
        <div class="context_text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur
          quisquam modi unde mollitia animi minima rerum inventore quaerat ab
          earum, tempore ex iure eos pariatur incidunt accusantium atque
          similique esse. Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Molestias, iste neque nemo placeat impedit non. Ad, a. Minima
          consequatur, corrupti numquam, nam laboriosam atque reprehenderit,
          vitae tempore ad laudantium a?
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "context",
};
</script>

<style scoped>
.context_box {
  /* margin-bottom: 100vh; */
  margin-top: 10vh;
  background-color: rgb(97, 235, 143);
  box-shadow: 3px 3px 3px 2px rgba(0, 0, 0, 0.2);
  border-radius: 1rem;
  height: 50vh;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 100px;
}

.context_img {
  width: 30%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 25px;
}
.context_img img {
  width: 250px;
  height: 250px;
}
.context_textbox {
  width: 70%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  padding-left: 50px;
}
</style>
