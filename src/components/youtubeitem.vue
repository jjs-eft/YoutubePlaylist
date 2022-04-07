<template>
  <div class="youtubeitem">
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
    <div class="item">
      <div class="item_title">영상 제목</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "youtubeitem",
};
</script>

<style scoped>
.youtubeitem {
  border: 1px blue solid;
  margin: 5px auto;
  width: 1500px;
  height: 740px;
  display: flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.item {
  border: red 1px solid;
  max-width: 330px;
  max-height: 200px;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column-reverse;
  margin: 20px auto;
}

.item_title {
  font-size: 15px;
  width: 100%;
  height: 25px;
  padding-left: 5px;
  border: blue 1px solid;
}
</style>
