<script setup>
</script>

<template>
  <footer class="footer">
    <div class="footer__main container">
      <div class="footer__left">
        <img class="footer__left-logo" src="@/assets/img/yellowkitchen.png" alt="">
        <div class="footer__left-line"></div>
        <div class="footer__app">
          <img src="@/assets/img/app-img1-1.png" alt="">
          <img src="@/assets/img/app-img1-1.png" alt="">
        </div>
      </div>
      <div class="footer__center">
        <h6>About us</h6>
        <ul>
          <li>Concept</li>
          <li>Franchise</li>
          <li>Business</li>
          <li>Restaurant signup</li>
          <li>For Investors</li>
        </ul>
      </div>
      <div class="footer__center">
        <h6>About us</h6>
        <ul>
          <li>Concept</li>
          <li>Franchise</li>
          <li>Business</li>
          <li>Restaurant signup</li>
          <li>For Investors</li>
        </ul>
      </div>
      <div class="footer__center">
        <h6>Contact us</h6>
        <ul>
          <li>Yellow kitchen Paris 11</li>
          <li>69 avenue de la Republique 75011 <br> Paris</li>
          <li>0800 111 126</li>
          <li>contact@yellowkitchens.com</li>
        </ul>
      </div>
    </div>
    <div class="footer__bottom container">
      <div>
        <img src="@/assets/icon/insta.svg" alt="">
        <img src="@/assets/icon/insta.svg" alt="">
        <img src="@/assets/icon/insta.svg" alt="">
      </div>
      <div class="footer__bottom-list">
        <ul>
          <li>Privacy Policy</li>
          <li>Terms</li>
          <li>© 2020 Yellow kitchen</li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background: #3F4255;
  padding: 48px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  font-family: Martel sans-serif;
}

.footer__main {
  display: flex;
  justify-content: space-between;
  margin-bottom: 48px;
}

.footer__left-line {
  height: 1px;
  background: #D4D7E5;
  width: 296px;
  margin-bottom: 48px;
  margin-top: 48px;
}

.footer__center ul, li {
  list-style: none;
  margin: 0;
  padding: 0;
  color: white;
  font-weight: 700;
  font-size: 16px;
}
.footer__app {
  display: flex;
  gap: 8px;
}
.footer__center h6 {
  font-size: 24px;
  font-weight: 600;
  color: white;
  margin-bottom: 24px;
  font-family: Poppins  sans-serif;
}

.footer__bottom {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: auto;
}

.footer__bottom img {
  margin-right: 20px;
}

.footer__bottom ul, li {
  list-style: none;
  margin: 0;
  padding: 0;
  color: white;
  font-weight: 300;
  font-size: 14px;
}
.footer__bottom-list ul {
  display: flex;
  gap: 54px;
}
.footer__center ul {
  padding: 0;
}

.footer__center ul li {
  margin-bottom: 16px;
}

.footer__center ul li:last-child {
  margin-bottom: 0;
}
.footer__bottom {
  margin-top: 102px;
}
</style>