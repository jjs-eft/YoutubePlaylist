<template>
  <div class="main">
    <div class="modal_app">
      <insertmodal />
    </div>
    <div class="top">
      <img
        src="https://via.placeholder.com/200x50"
        class="logo_img"
        alt="..."
      />
      <div class="searchbar">
        <searchbar />
      </div>
      <menubtn /> <button class="temp" @click="openModal">임시</button>
    </div>
    <div class="middle">
      <playlist class="playlist" />
      <youtubeitem class="youtubeitem"></youtubeitem>
    </div>
  </div>
</template>

<script>
import Searchbar from "./components/searchbar.vue";
import Playlist from "./components/playlist.vue";
import Youtubeitem from "./components/youtubeitem.vue";
import menubtn from "./components/menubtn.vue";
import insertmodal from "./components/insertmodal.vue";
export default {
  name: "App",
  components: {
    Searchbar,
    Playlist,
    Youtubeitem,
    menubtn,
    insertmodal,
  },

  methods: {
    openModal() {
      console.log("temp");
      const modal_app = document.querySelector(".modal_app");
      modal_app.classList.add("_on");
    },
  },
};
</script>

<style>
.top {
  width: 100%;
  max-width: 1700px;
  margin: 25px auto;
  margin-left: 80px;
  display: flex;
}

.logo_img {
  max-width: 200px;
  max-height: 50px;
  width: 100%;
  height: 100%;
  border-radius: 5px;
}

.searchbar {
  width: 100%;
  height: 100%;
  margin-top: 5px;
  margin-left: 10%;
  margin-right: 5px;
  display: flex;
}

.middle {
  margin: 20px auto;
  max-width: 1850px;
  width: 100%;
  min-height: 765px;
  height: 100%;
  display: flex;
  border: 2px gray solid;
  border-radius: 10px;
  justify-content: space-around;
}

.playlist {
  max-width: 300px;
  max-height: 700px;
  width: 100%;
  height: 100%;
  margin-left: 15px;
  margin-top: 50px;
}
.youtubeitem {
  margin: 5px auto;
  max-width: 1500px;
  max-height: 800px;
  width: 100%;
  height: 100%;
}

.modal_app {
  display: none;
}

.modal_app._on {
  display: flex;
}
</style>
