<script setup>
</script>

<template>
  <div class="info-wrapper">
    <div class="info container">
      <div class="info__list">
        <div class="info__list-item">
          <span>1</span>
          <p>kitchen</p>
        </div>
        <div class="info__list-item">
          <span>1</span>
          <p>kitchen</p>
        </div>
        <div class="info__list-item">
          <span>1</span>
          <p>kitchen</p>
        </div>
        <div class="info__list-item">
          <span>1</span>
          <p>kitchen</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.info {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 284px;
}
.info-wrapper {
  background: url("@/assets/img/bg.png") no-repeat;
  background-size: cover;
}
.info__list-item {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.info__list {
  display: flex;
  gap: 53px;
}
.info__list-item span {
  background: #FFE145;
  height: 126px;
  width: 126px;
  border-radius: 50%;
  color: #3F4255;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 58px;
  font-weight: 600;
  padding-top: 5px;
  position: relative;
  font-family: Poppins sans-serif;
}

.info__list-item span::after {
  content: "";
  position: absolute;
  top: -20px;
  left: 0;
  width: 126px;
  height: 126px;
  border-radius: 50%;
  border: 1px solid #B79C10;
  background-color: transparent;
  z-index: 1;
}
</style>