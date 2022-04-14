<template>
  <div class="modal">
    <div class="backdrop" @click="$emit('close-modal')"></div>
    <div class="modal_content">
      <div class="closebtn_div">
        <button
          type="button"
          class="btn-close"
          aria-label="Close"
          @click="$emit('close-modal')"
        ></button>
      </div>
      <slot />
    </div>
  </div>
</template>

<script>
export default {
  name: "modalview",
};
</script>

<style scoped>
.modal {
  /* background-color: #aaaa; */
  display: flex;
  justify-content: center;
  align-items: center;

  width: 100%;
  height: 100%;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.backdrop {
  width: 100%;
  height: 100%;
  background-color: #aaaa;
  display: flex;
  position: fixed;
  transition-delay: all 2s;
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
</style>
