<script setup>
import img from "@/assets/img/burgers.png"
import photo from "@/assets/img/logo-rest.png"
const restaurants = [
  { id: 1, image: img, logo: photo },
  { id: 1, image: img, logo: photo },
  { id: 1, image: img, logo: photo },
  { id: 1, image: img, logo: photo },
];
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
      <div
          v-for="restaurant in restaurants"
          :key="restaurant.id"
          class="restarans__list-item"
      >
        <img :src="restaurant.image" alt="Restaurant Image" />
        <img class="restarans__list-item-title" :src="restaurant.logo" alt="Restaurant Logo" />
      </div>
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
  background: #fff;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);

}

.restarans__list {
  display: flex;
  justify-content: space-between;
  margin-top: 48px;
  gap: 24px;
}
.restarans__list-item-title {
  height: 68px;
  width: 149px;
  margin-top: 25px;
  margin-bottom: 18px;
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