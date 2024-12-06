<script setup>
import img from "@//assets/img/bagel.png"

const specialties = [
  { id: 1, name: "Bagel", img: img },
  { id: 2, name: "Bagel", img: img },
  { id: 3, name: "Bagel", img: img },
  { id: 4, name: "Bagel", img: img },
  { id: 5, name: "Bagel", img: img },
  { id: 6, name: "Bagel", img: img },
  { id: 7, name: "Bagel", img: img },
  { id: 8, name: "Bagel", img: img},
];
</script>

<template>
  <div class="special container">
    <div class="special__header">
      <h1>Specialities</h1>
      <button class="special__btn">
        <span>show all</span>
      </button>
    </div>
    <div class="special__list">
      <div
          v-for="item in specialties"
          :key="item.id"
          class="special__list-item"
      >
        <img :src="item.img" :alt="item.name" />
        <span>{{ item.name }}</span>
      </div>
    </div>
  </div>
</template>

<style scoped>
.special{
  padding-bottom: 72px;
  padding-top: 72px;
}
.special h1 {
  color: #3F4255;
  font-size: 36px;
  font-family: "Poppins", sans-serif;
  font-weight: 300;
}
.special__header {
  display: flex;
  justify-content: space-between;
}
.special__btn {
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
.special__list-item {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 136px;
  width: 136px;
  box-shadow: 1px 2px 3px 4px rgba(0, 0, 0, 0.3);
}
.special__list-item span {
  margin-top: 16px;
}
.special__list {
  display: flex;
  margin-top: 48px;
  justify-content: space-between;
  align-items: center;
}
</style>