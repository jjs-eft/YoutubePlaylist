<template>
  <div class="youtubeitem">
    <div class="item">
      <iframe
        src="https://www.youtube.com/embed/k0z6me9hYwc"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
        class="youtube_item_temp"
      ></iframe>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
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
  margin: 5px auto;
  width: 1500px;
  height: 740px;
  display: flex;
  flex-wrap: wrap;
  align-content: flex-start;
  background-color: #f5e0a3;
  border-radius: 10px;
}

.item {
  border: gray 1px solid;
  max-width: 330px;
  max-height: 200px;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  margin: 20px auto;
}

.item_title {
  font-size: 15px;
  width: 100%;
  height: 25px;
  padding-left: 5px;
  border: blue 1px solid;
}

.youtube_item_temp {
  width: 100%;
  height: 100%;
}

.temp_img {
  width: 100%;
  height: 100%;
}
</style>
