<template>
  <section class="section">
    <div class="process-body">
      <div class="container">
        <div class="process-text">
          <p class="process-text-p1">Making brands stand out</p>
          <p class="process-text-p1 second-p1">is our obsession</p>
          <hr />
          <p class="process-text-p2">Let us help your brand stand out.</p>
          <img src="../assets/X.png" alt="img" />
        </div>
      </div>
    </div>
    <div class="process-foot">
      <div class="container">
        <div class="foot-items">
          <p>
            Minimalist is a full-service digital creative agency located in
            Ontorio Canada. We focus on design, consulting, technology, and
            photography. We’ve been building unique digital products, platforms,
            and experiences for the past 6 years. Let us help your company grow.
          </p>
          <button>Get in Touch</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
.section {
  width: 100%;
  height: 600px;
  margin-bottom: 60px;
  .process-body {
    width: 100%;
    height: 391px;
    // max-width: 1600px;
    // margin: 0 auto;
    // border: 1px solid rgb(239, 243, 11);

    background: url("../assets/backgroun-img.jpg"), lightgray 50%;
    background-repeat: no-repeat;
    object-fit: cover;
    display: flex;
    background-size: cover;
    align-items: center;
    align-content: center;
    justify-content: center;
    background-position: center;
    padding-top: 80px;
    padding-bottom: 80px;
    position: relative;

    .process-text {
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      // border: 1px solid blue;
      text-align: center;
      align-items: center;
      img {
        position: absolute;
        bottom: -26px;
        left: calc(50% - 26px);
        width: 52px;
        height: 52px;
        flex-shrink: 0;
      }
      .process-text-p1 {
        color: #fff;
        text-align: center;
        font-family: Montserrat;
        font-size: 44px;
        font-style: normal;
        font-weight: 400;
        line-height: 55px; /* 125% */
        text-transform: uppercase;
      }

      .second-p1 {
        margin-bottom: 28px;
      }
      hr {
        width: 80px;
        height: 2px;
        flex-shrink: 0;
        background: #fff;
        border-style: none;
        margin-bottom: 25px;
      }
      .process-text-p2 {
        color: rgba(255, 255, 255, 0.81);
        text-align: center;
        font-family: Vollkorn;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px; /* 133.333% */
      }
    }
  }

  .process-foot {
    width: 100%;
    height: 289px;
    background: #fefec9;
    padding-top: 60px;
    padding-bottom: 60px;
    // border: 1px solid red;
    display: flex;
    justify-content: center;

    .foot-items {
      width: 100%;
      // border: 1px solid red;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      gap: 40px;
      p {
        color: #47474f;
        text-align: center;
        font-family: Vollkorn;
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        line-height: 25px; /* 138.889% */
        // border: 1px solid red;
      }
      button {
        width: 159px;
        color: #47474f;
        text-align: center;
        font-family: Vollkorn;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px; /* 125% */
        height: 53px;
        flex-shrink: 0;
        background: #fefec9;
        border-style: none;
        border: 1px solid #47474f;
      }
    }
  }
}
@media (max-width: 990px) {
  .section .process-body .process-text .process-text-p1 {
    font-size: 38px;
  }
}
@media (max-width: 770px) {
  .section .process-body .process-text .process-text-p1 {
    font-size: 32px;
  }
  .section .process-foot {
    height: 327px;
  }
}
@media (max-width: 519px) {
  .section .process-body .process-text .process-text-p1 {
    font-size: 28px;
  }
  .section .process-foot {
    height: 327px;
  }
  .section .process-foot .foot-items button {
    width: 150px;
    height: 45px;
  }
  .section .process-foot .foot-items {
    gap: 30px;
  }
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .section .process-body .process-text {
    width: 90%;
  }
}
</style>
