<script setup>
</script>

<template>
  <div class="header__wrapper">
    <header class="header container">
      <div class="header__title">
        <img src="@/assets/img/Logo.png" alt="">
      </div>
      <div class="header__nav">
        <ul class="header__nav__list">
          <li>
            <img src="@/assets/icon/person.svg" alt="">
            <span>Log in</span>
          </li>
          <li>
            <img src="@/assets/icon/cart.svg" alt="">
            <span>0</span>
          </li>
          <li class="header__nav__list__burger">
            <span></span>
            <span></span>
            <span></span>
          </li>
        </ul>
      </div>
    </header>
  </div>

</template>

<style scoped>
.header__wrapper {
  border-bottom: 1px solid #D4D7E5;
}
.header {
  display: flex;
  justify-content: space-between;
  padding: 12px 0;
}

.header__nav__list {
  display: flex;
  gap: 48px;
  align-items: center;
}

.header__nav__list li {
  display: flex;
  align-items: center;
  font-weight: 700;
  font-size: 16px;
  color: #9093A6;
}

.header__nav__list__burger {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 18px;
  width: 48px;
  cursor: pointer;
  background: white;
  border-radius: 50px;
}

.header__nav__list__burger span {
  display: block;
  height: 2px;
  width: 24px;
  background: #9093A6;
  border-radius: 2px;
}
</style>