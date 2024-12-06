<script setup>

</script>

<template>
  <div class="near">
    <div class="nearest container">
      <div class="nearest__left">
        <h1>Your nearest restaurants</h1>
        <p>Each kitchen works with its own delivery area <br> to deliver food to you as soon as possible</p>
      </div>
      <div class="nearest__right">
        <img class="location" src="@/assets/icon/location.svg" alt="">
        <input class="nearest__right-input" placeholder="Enter delivery address" type="text" />
        <button class="nearest__right-btn">send</button>
      </div>
    </div>
  </div>

</template>

<style scoped>
.near {
  background: #F2F4FA;
}
.nearest {
  display: flex;
  gap: 159px;
  align-items: center;
  padding-top: 80px;
  padding-bottom: 81px;
  justify-content: space-between;
}
.nearest__left h1 {
  font-size: 36px;
  font-weight: 300;
  color: #3F4255;
  font-family: Poppins sans-serif;
}
.nearest__left p {
  color: #3F4255;
  font-size: 16px;
  font-weight: 400;
  font-family: Martel sans-serif;
}
.nearest__right {
  display: flex;
  gap: 4px;
}
.nearest__right-btn {
  border: none;
  background: #FFE145;
  color: #B79C10;
  padding: 26px 24px;
  border-radius: 4px;
  cursor: pointer;
}
.nearest__right-input {
  border-radius: 4px;
  border: none;
  width: 336px;
}
.nearest__right-input::placeholder {
  color: #9093A6;
  font-size: 16px;
  font-weight: 400;
  padding-left: 48px;
}
.location {
  position: relative;
  right: -40px;
  top: -1px;
}
</style>