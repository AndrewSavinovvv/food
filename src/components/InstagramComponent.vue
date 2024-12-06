<script setup>
</script>

<template>
  <div class="inst container">
    <h1><span>#YellowKitchens</span> in instagram</h1>
    <div class="images">
      <img src="@/assets/img/inst-img.png" alt="">
      <img src="@/assets/img/inst-img.png" alt="">
      <img src="@/assets/img/inst-img.png" alt="">
      <img src="@/assets/img/inst-img.png" alt="">
    </div>
  </div>
</template>

<style scoped>
.inst {
  display: flex;
  flex-direction: column;
 padding-bottom: 72px;
  padding-top: 72px;
}

.inst h1 {
  font-size: 36px;
  color: #9093A6;
  font-weight: 300;
  font-family: Poppins sans-serif;
  text-align: left;
}

.inst h1 span {
  color: #313030;
}

.images {
  display: flex;
  gap: 24px;
  margin-top: 21px;
}

.images img {
  width: 100%;
  max-width: 300px;
  height: auto;
}
</style>