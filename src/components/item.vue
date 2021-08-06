<template>
  <div class="container item_content" id="item">
    <div class="item_firstflex">
      <div class="item_box">
        <div class="item_detail">
          <div class="item_pic">
            <img alt="Vue logo" src="@/assets/logo.png" />
          </div>
          <div class="item_text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quaerat,
            voluptas ratione et maiores voluptates excepturi natus impedit, a
            iusto deleniti cum quas in minus maxime possimus accusantium nemo
            magni?
          </div>
        </div>
      </div>

      <div class="item_box">
        <div class="item_detail">
          <div class="item_pic">
            <img alt="Vue logo" src="@/assets/logo.png" />
          </div>
          <div class="item_text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quaerat,
            voluptas ratione et maiores voluptates excepturi natus impedit, a
            iusto deleniti cum quas in minus maxime possimus accusantium nemo
            magni?
          </div>
        </div>
      </div>
    </div>
    <div class="item_secondflex">
      <div class="item_box">
        <div class="item_detail">
          <div class="item_pic">
            <img alt="Vue logo" src="@/assets/logo.png" />
          </div>
          <div class="item_text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quaerat,
            voluptas ratione et maiores voluptates excepturi natus impedit, a
            iusto deleniti cum quas in minus maxime possimus accusantium nemo
            magni?
          </div>
        </div>
      </div>

      <div class="item_box">
        <div class="item_detail">
          <div class="item_pic">
            <img alt="Vue logo" src="@/assets/logo.png" />
          </div>
          <div class="item_text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quaerat,
            voluptas ratione et maiores voluptates excepturi natus impedit, a
            iusto deleniti cum quas in minus maxime possimus accusantium nemo
            magni?
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "item",
};
</script>
<style scoped>
.item_content {
  height: 200vh;
  background-color: rgb(97, 235, 143);
  border-radius: 1rem;
  padding: 10vh 15vh;
  box-shadow: 3px 3px 3px 2px rgba(0, 0, 0, 0.2);
  margin-top: 15vh;
  margin-bottom: 20vh;
}
.item_firstflex,
.item_secondflex {
  margin-bottom: 20vh;
  display: flex;
  justify-content: space-between;
}
.item_box {
  height: 33rem;
  width: 25rem;
  border-radius: 3rem;
  padding: 10px 10px;
  /* background-color: rgb(97, 235, 143); */
  background-color: rgba(255, 255, 255, 0.925);
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 3px 3px 3px 2px rgba(0, 0, 0, 0.2);
}
.item_detail {
  display: grid;
  grid-template-rows: 1fr 1fr;
  width: 90%;
  height: 90%;
}
.item_pic {
  height: 150px;
  margin: 10px auto;
}
.item_text {
  width: 95%;
  margin: 0 auto;
  height: 50%;
  padding: 5px 5px;
}
</style>
