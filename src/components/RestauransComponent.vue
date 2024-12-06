<script setup>

</script>

<template>
  <div class="restarans container">
    <div class="restarans__header">
      <h1>Restaurants</h1>
      <button class="restarans__btn">
        <span>show all</span>
      </button>
    </div>
    <div class="restarans__list">
<!--      <img class="restarans__list-left" src="@/assets/img/Button.png" alt="">-->
      <div class="restarans__list-item">
        <img src="@/assets/img/burgers.png" alt="">
        <img class="restarans__list-item-title" src="@/assets/img/logo-rest.png" alt="">
      </div>
      <div class="restarans__list-item">
        <img src="@/assets/img/burgers.png" alt="">
        <img class="restarans__list-item-title" src="@/assets/img/logo-rest.png" alt="">
      </div>
      <div class="restarans__list-item">
        <img src="@/assets/img/burgers.png" alt="">
        <img class="restarans__list-item-title" src="@/assets/img/logo-rest.png" alt="">
      </div>
      <div class="restarans__list-item">
        <img src="@/assets/img/burgers.png" alt="">
        <img class="restarans__list-item-title" src="@/assets/img/logo-rest.png" alt="">
      </div>
<!--      <img class="restarans__list-right" src="@/assets/img/Button1.png" alt="">-->
    </div>
  </div>
</template>

<style scoped>
.restarans {
  padding-top: 48px;
  padding-bottom: 72px;
}
.restarans h1 {
  color: #3F4255;
  font-size: 36px;
  font-family: "Poppins", sans-serif;
  font-weight: 300;
}
.restarans__header {
  display: flex;
  justify-content: space-between;
}
.restarans__btn {
background: #F2F4FA;
  color: #9093A6;
  border: none;
  cursor: pointer;
  padding: 14px 24px;
  font-family: "Martel", serif;
  font-size: 16px;
  font-weight: 700;
  border-radius: 10px;
}
.restarans__list-item {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.restarans__list {
  display: flex;
  justify-content: space-between;
  margin-top: 48px;
}
.restarans__list-item-title {
  height: 68px;
  width: 149px;
  margin-top: 25px;
}
.restarans__list-right {
  position: relative;
  left: -23px;
  top: 88px;
  height: 48px;
  width: 48px;
  cursor: pointer;
}
.restarans__list-left {
  position: relative;
  left: 20px;
  top: 88px;
  height: 48px;
  width: 48px;
  cursor: pointer;
}

</style>