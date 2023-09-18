<template>
  <div class="header">
    <div class="container">
      <div class="nav-itmes">
        <div class="nav-icon">
          <img src="../assets/minimal-logo.jpg" alt="#" />
          <p>Minimal</p>
        </div>
        <div class="nav-links">
          <a href="#"> process </a>
          <a href="#"> projects </a>
          <a href="#"> team </a>
          <a href="#"> contact </a>
        </div>
        <div class="menu-icon">
          <i class="fa-solid fa-bars"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  align-content: center;
  padding: 18px 0px;
  // border: 1px solid rgb(179, 235, 9);
}
.nav-itmes {
  width: 100%;
  // border: 1px solid black;
  display: flex;
  justify-content: space-between;
  align-items: center;
  align-content: center;
  // align-content: center;
}
.nav-icon {
  // width: 16.5%;
  display: flex;
  align-items: center;
  align-content: center;
  justify-content: center;
  gap: 18px;
}

.nav-icon img {
  // width: 50%;
  // height: 70px;
  flex-shrink: 0;
  // background: url(<path-to-image>), lightgray 50% / cover no-repeat;
}
.nav-icon p {
  width: 50%;
  color: #333;
  font-family: Oswald;
  font-size: 22px;
  font-style: normal;
  font-weight: 400;
  line-height: 38px; /* 172.727% */
  text-transform: uppercase;
}
.nav-links {
  // width: 38%;
  display: flex;
  // padding: 23px 0px 0px;
  // justify-content: flex-end;
  // align-items: flex-start;
  align-items: center;
  align-content: center;
  justify-content: center;
  gap: 34px;
}
.nav-links a {
  color: #404040;
  font-family: Montserrat;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 166.667% */
  text-transform: uppercase;
  text-decoration: none;
}
.menu-icon {
  display: none;
  font-size: 30px;
}
@media (max-width: 520px) {
  .nav-links {
    display: none;
  }
  .menu-icon {
    display: block;
  }
}
</style>
