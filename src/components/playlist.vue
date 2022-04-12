<template>
  <div class="playlist">
    <div class="playlist_title">목록</div>
    <ol class="playlist_items">
      <li class="playlist_item">
        1번 리스트
        <div class="btn-group">
          <button
            class="btn btn-secondary btn-sm dropdown-toggle"
            type="button"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            메뉴
          </button>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">선택</a></li>
            <li><a class="dropdown-item" href="#">이름변경</a></li>
            <li><a class="dropdown-item" href="#">공유하기</a></li>
            <li><a class="dropdown-item" href="#">삭제</a></li>
          </ul>
        </div>
      </li>
    </ol>
  </div>
</template>

<script>
export default {
  name: "playlist",
};
</script>

<style scoped>
.playlist {
  width: 300px;
  height: 680px;
  margin-left: 15px;
  margin-top: 50px;
  background-color: #f5e0a3;

  border-radius: 10px;
}

.playlist_title {
  background-color: #eea282;
  border-top-right-radius: 10px;
  border-top-left-radius: 10px;
  max-width: 300px;
  width: 100%;
  text-align: center;
}

.playlist_item {
  margin: 5px;
}
</style>
