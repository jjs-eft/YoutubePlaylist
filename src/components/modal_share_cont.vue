<template>
  <div class="form">
    <input
      type="text"
      class="form-control"
      placeholder="공유값"
      id="paste_cont"
      readonly
    />
    <button class="btn btn-outline-secondary" type="button" id="paste_btn">
      복사
    </button>
  </div>
</template>

<script>
export default {
  name: "modal_share_cont",
};
</script>

<style scoped>
.form {
  margin-top: 5px;
  width: 100%;
  height: 80%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#paste_cont {
  width: 90%;
  height: 80%;
  margin-bottom: 15px;
  display: flex;
}

#paste_btn {
  white-space: nowrap;
  font-size: 13px;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
