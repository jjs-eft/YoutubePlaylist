<template>
  <div class="add_form">
    <div class="youtube_add">
      <input
        type="text"
        class="form-control"
        placeholder="유튜브 영상을 추가해주세요."
      />
      <button class="btn btn-outline-secondary" type="button" id="add_btn">
        추가
      </button>
    </div>
    <div class="playlist_add">
      <input
        type="text"
        class="form-control"
        placeholder="플레이리스트를 추가해주세요."
      />
      <button class="btn btn-outline-secondary" type="button" id="add_btn">
        추가
      </button>
    </div>
    <button
      class="btn btn-outline-secondary"
      type="button"
      id="empty_list_add_btn"
    >
      새로운 빈 리스트 추가
    </button>
  </div>
</template>

<script>
export default {
  name: "modal_add_cont",
};
</script>

<style scoped>
.add_form {
  margin-top: 30px;
  width: 100%;
  height: 70%;
  display: flex;

  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
}

.youtube_add {
  display: flex;
  width: 95%;
  height: 25px;
}

.playlist_add {
  display: flex;
  width: 95%;
  height: 25px;
}

#add_btn {
  white-space: nowrap;
  font-size: 13px;
  display: flex;
  justify-content: center;
  align-items: center;
}

#empty_list_add_btn {
  width: 300px;
  height: 35px;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
