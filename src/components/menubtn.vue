<template>
  <div class="btn_group">
    <button class="pag_btn">
      <img src="../assets/arrow_left.png" alt="" />
    </button>
    <button class="pag_btn">
      <img src="../assets/arrow_right.png" alt="" />
    </button>
    <button class="insertbtn">추가하기</button>
  </div>
</template>

<script>
export default {
  name: "menubtn",
};
</script>

<style scoped>
.btn_group {
  width: 300px;
  height: 40px;
  margin-left: 30px;
  margin-top: 5px;
  border: 1px solid black;
  padding: 5px;
  display: flex;
  justify-content: space-around;
}

.pag_btn {
  border: 0px;
}

.insertbtn {
  border: 0px;
}
</style>
