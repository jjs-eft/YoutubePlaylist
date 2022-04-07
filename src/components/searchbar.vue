<template>
  <div class="input-group mb-3">
    <input
      type="text"
      class="form-control"
      placeholder="영상을 검색해주세요."
      aria-label="영상을 검색해주세요."
    />
    <button class="btn btn-outline-secondary" type="button" id="button-addon2">
      검색
    </button>
  </div>
</template>

<script>
export default {
  name: "searchbar",
};
</script>

<style scoped>
.form-control {
  width: 100%;
  max-width: 1000px;
}

#button-addon2 {
  width: 100%;
  max-width: 60px;
}
</style>
