<template>
  <div class="modal">
    <div class="modal_content">
      <div class="closebtn_div">
        <button type="button" class="btn-close" aria-label="Close"></button>
      </div>

      <div class="add_form">
        <div class="youtube_add">
          <input
            type="text"
            class="form-control"
            placeholder="유튜브 영상을 추가해주세요."
          />
          <button
            class="btn btn-outline-secondary"
            type="button"
            id="button-addon2"
          >
            추가
          </button>
        </div>
        <div class="playlist_add">
          <input
            type="text"
            class="form-control"
            placeholder="플레이리스트를 추가해주세요."
          />
          <button
            class="btn btn-outline-secondary"
            type="button"
            id="button-addon2"
          >
            추가
          </button>
        </div>
      </div>
    </div>
    <div class="backdrop"></div>
  </div>
</template>

<script>
export default {
  name: "insertmodal",
};
</script>

<style scoped>
.modal {
  /* background-color: #aaaa; */
  display: flex;
  justify-content: center;
  align-items: center;

  width: 100%;
  max-width: 500px;
  height: 300px;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.modal_content {
  background-color: #ceefe4;
  width: 100%;
  max-width: 500px;
  height: 300px;
  position: fixed;
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}
/* #d9d9f3, #ceefe4, #9dd3a8 */
.closebtn_div {
  display: flex;
  justify-content: flex-end;
  width: 100%;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  background-color: #9dd3a8;
}
.add_form {
  margin-top: 30px;
  width: 100%;
  height: 60%;
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

#button-addon2 {
  white-space: nowrap;
  font-size: 13px;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
