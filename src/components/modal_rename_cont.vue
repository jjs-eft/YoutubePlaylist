<template>
  <div class="form">
    <div class="rename_form">
      <input type="text" class="form-control" placeholder=" 이름 변경 " />
      <button class="btn btn-outline-secondary" type="button" id="change_btn">
        변경
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "modal_rename_cont",
};
</script>

<style scoped>
.form {
  margin-top: 30px;
  width: 100%;
  height: 60%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.rename_form {
  display: flex;
  width: 80%;
  height: 25px;
}

#change_btn {
  white-space: nowrap;
  font-size: 13px;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
