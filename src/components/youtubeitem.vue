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
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
    </div>
    <div class="item">
      <img src="../assets/temp.png" alt="tempimg" class="temp_img" />
      <button class="item-menu">⨯</button>
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
  max-width: 350px;
  max-height: 200px;
  width: 100%;
  height: 100%;
  display: flex;

  margin: 20px auto;
}

.youtube_item_temp {
  width: 100%;
  height: 100%;
  border-radius: 5px;
  border-top-right-radius: 0px;
}

.temp_img {
  width: 100%;
  height: 100%;
  border-radius: 5px;
  border-top-right-radius: 0px;
}

.item-menu {
  width: 13px;
  height: 40px;
  border: 1px solid gray;
  background-color: gray;
  border-top-right-radius: 6px;
  border-bottom-right-radius: 6px;
  color: gray;
  font-size: 1px;
}

.item-menu:hover {
  width: 30px;
  height: 40px;
  border: black 1px solid;
  transition: all 2s;
  background-color: #9dd3a8;
  border: 1px solid #9dd3a8;
  font-size: 30px;
  color: black;
  display: flex;
  justify-content: center;
  align-items: flex-end;
}
</style>
