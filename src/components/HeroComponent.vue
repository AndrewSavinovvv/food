<script setup>
</script>

<template>
  <div class="hero container">
    <div class="hero__left">
      <h1>Your Food court at home</h1>
      <div class="hero__left__btn">
        <button class="hero__left__delivery">
          <h6 class="btn__title">Delivery</h6>
          <span>Order in</span>
        </button>
        <button class="hero__left__take">
          <h6 class="btn__title">Takeout</h6>
          <span>Grab and go</span>
        </button>
      </div>
      <div class="hero__left__list">
        <div class="hero__left__list-item">
          <img src="@/assets/img/delivery.png" alt="">
          <p>Free delivery from 29 euros</p>
        </div>
        <div class="hero__left__list-item">
          <img src="@/assets/img/delivery.png" alt="">
          <p>Free delivery from 29 euros</p>
        </div>
        <div class="hero__left__list-item">
          <img src="@/assets/img/delivery.png" alt="">
          <p>Free delivery from 29 euros</p>
        </div>
      </div>
    </div>
    <div class="hero__right">
      <div class="hero__right__img">
        <img src="@/assets/img/hero-bg.png" alt="">
      </div>
      <img class="hero__right__rokula" src="@/assets/img/rucola-png.png" alt="">
      <img class="hero__right__text" src="@/assets/img/Photo-description.png" alt="">
    </div>

  </div>
</template>

<style scoped>
.hero {
  display: flex;

}

.hero__left {
  display: flex;
  flex-direction: column;
  padding-top: 120px;
}

.hero__left h1 {
  color: #3F4255;
  font-size: 58px;
  font-family: "Poppins", sans-serif;
  font-weight: 300;
  margin-bottom: 88px;
}

.hero__left__delivery, .hero__left__take {
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  border: 2px solid #FFE145;
  background: none;
  padding: 18px 24px;
  cursor: pointer;
  font-weight: 400;
  font-size: 12px;
}
.hero__left__take {
  margin-left: 24px;
}
.hero__left__delivery span, .hero__left__take span {
  font-family: "Martel", serif;
}

.btn__title {
  font-weight: bold;
  font-size: 16px;
}
.hero__right__img {
  position: relative;
}
.hero__right__rokula{
  position: absolute;
  bottom: 218px;
  right: 940px;
}
.hero__right__text {
  position: absolute;
  right:300px;
  bottom: 218px;
}

.hero__left__list {
  display: flex;
  align-items: center;
  margin-top: 304px;
  gap: 46px;
}
.hero__left__list-item p {
  color:#3F4255;
  font-size: 16px;
  font-weight: 400;
}
.hero__left__list-item  {
  display: flex;
  align-items: center;
  gap: 16px;
}
.hero__left__list-item img {
  width: 46px;
  height: 46px;
}
</style>