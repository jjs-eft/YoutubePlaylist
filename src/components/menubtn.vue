<template>
  <div class="btn_group">
    <button class="pag_btn">
      <img src="../assets/arrow_left.png" alt="" />
    </button>
    <button class="pag_btn">
      <img src="../assets/arrow_right.png" alt="" />
    </button>
    <button class="insertbtn" @click="$emit('open-modal-add')">⫶⫶⫶</button>
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
  border: 2px solid gray;
  padding: 5px;
  display: flex;
  justify-content: space-around;
  border-radius: 5px;
}

.pag_btn {
  border: 1px solid gray;
  border-radius: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.insertbtn {
  border: 1px solid gray;
  border-radius: 5px;
  width: 100px;
  height: 26px;

  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
