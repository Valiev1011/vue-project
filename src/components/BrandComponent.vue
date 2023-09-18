<template>
  <section class="brand">
    <div class="container">
      <div class="brand-items">
        <p class="outp">How we make brands thrive</p>
        <hr />
        <div class="brand-body">
          <div class="target">
            <div class="bg-img">
              <img src="../assets/circle.png" alt="" />
            </div>
            <h1>SET a target</h1>
            <p class="innerp">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
          <div class="target">
            <div class="bg-img">
              <img src="../assets/lineyka.png" alt="" />
            </div>
            <h1>SET a target</h1>
            <p class="innerp">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
          <div class="target">
            <div class="bg-img">
              <img src="../assets/diogramma.png" alt="" />
            </div>
            <h1>SET a target</h1>
            <p class="innerp">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
.brand {
  width: 100%;
  padding-top: 70px;
  padding-bottom: 70px;
  display: flex;
  align-items: center;
  align-content: center;
  justify-content: center;

  // border: 1px solid red;

  .brand-items {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 10px;
    // border: 1px solid red;

    .outp {
      color: #333;
      text-align: center;
      font-family: Montserrat;
      font-size: 23px;
      font-style: normal;
      font-weight: 400;
      line-height: 36px; /* 156.522% */
      text-transform: uppercase;
    }
    hr {
      width: 80px;
      height: 2px;
      flex-shrink: 0;
      background: rgba(0, 0, 0, 0.09);
      margin-top: 28px;
      margin-bottom: 43px;
      border-style: none;
    }
    .brand-body {
      width: 100%;
      display: flex;
      flex-wrap: wrap;
      padding-right: 0px;
      justify-content: center;
      align-items: flex-start;
      flex-shrink: 0;
      // border: 1px solid red;

      .target {
        width: 33.3%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding-left: 10px;
        padding-right: 10px;
        padding-bottom: 10px;
        .bg-img {
          width: 100%;
          display: flex;
          justify-content: center;
          align-items: center;
          background: #f5f5f5;
          padding-top: 50px;
          padding-bottom: 50px;
          // padding: 50px 87px;
          // border: 1px solid red;
        }
        h1 {
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px; /* 125% */
          text-transform: uppercase;
          margin-top: 38px;
          margin-bottom: 20px;
        }
        .innerp {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 15px;
          font-style: normal;
          font-weight: 400;
          line-height: 22px;
        }
      }
    }
  }
}
@media (max-width: 770px) {
  .brand .brand-items .brand-body .target {
    width: 50%;
  }
}
@media (max-width: 519px) {
  .brand .brand-items .brand-body .target {
    width: 90%;
    margin-top: 20px;
  }
}
</style>
