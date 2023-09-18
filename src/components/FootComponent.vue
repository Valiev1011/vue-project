<template>
  <section class="footer">
    <div class="container">
      <div class="foot-items">
        <div class="foot-body">
          <input type="text" placeholder="Name" />
          <input type="email" placeholder="Email" />
          <input type="text" placeholder="Budget" />
          <textarea
            cols="30"
            rows="10"
            placeholder="Describe your project"
          ></textarea>
          <button class="foot-btn">Send Message</button>
        </div>
        <div class="foot-img">
          <img src="../assets/logo_under.png" alt="img" />
          <p>Minimal Template made in Webflow. All rights reserved.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
.footer {
  width: 100%;
  display: flex;
  align-items: center;
  align-content: center;
  justify-content: center;
  background: #000;
  padding-top: 69px;
  padding-bottom: 69px;
  .foot-items {
    width: 60%;
    display: flex;
    flex-direction: column;
    gap: 15px;
    padding-top: 10px;
    padding-bottom: 20px;
    margin: 0 auto;
    align-items: center;
    align-content: center;
    justify-content: center;
    // padding: 0px 188px 5.953px 188px;
    align-items: center;

    .foot-body {
      width: 100%;
      display: flex;
      align-items: center;
      align-content: center;
      justify-content: center;
      flex-direction: column;
      padding-bottom: 22px;
      input:nth-child(odd) {
        background-color: rgba(255, 255, 255, 0.18);
      }
      input:nth-child(2n) {
        background-color: rgba(255, 255, 255, 0.2);
      }
      input {
        width: 100%;
        padding: 18px 30px;
        font-size: 16px;
        color: #fff;
        font-family: Vollkorn;
        font-style: italic;
        font-weight: 400;
        line-height: 22px;
        border-style: none;
        outline: none;
      }
      input::placeholder {
        color: white;
      }
      textarea {
        width: 100%;
        padding: 18px 30px;
        font-size: 16px;
        color: #fff;
        font-family: Vollkorn;
        font-style: italic;
        font-weight: 400;
        line-height: 22px;
        background: hsla(0, 0%, 100%, 0.2);
        height: 127px;
        flex-shrink: 0;
        resize: none;
        border: none;
        outline: none;
      }
      textarea::placeholder {
        color: white;
      }
      .name {
        width: 100%;
        display: flex;
        display: flex;
        align-items: center;
        align-content: center;
        justify-content: center;
        background: rgba(255, 255, 255, 0.18);
        p {
          color: #fff;
          text-align: center;
          font-family: Vollkorn;
          font-size: 17px;
          font-style: italic;
          font-weight: 400;
          line-height: 22px; /* 129.412% */
          //   padding: 18px 493px 17px 30px;
          padding-left: 18px;
          padding-right: 18px;
        }
      }
      .email {
        width: 100%;
        display: flex;
        display: flex;
        align-items: center;
        align-content: center;
        justify-content: center;
        background: rgba(255, 255, 255, 0.2);
        p {
          color: #fff;
          text-align: center;
          font-family: Vollkorn;
          font-size: 17px;
          font-style: italic;
          font-weight: 400;
          line-height: 22px; /* 129.412% */
          //   padding: 18px 493px 17px 30px;
          padding-left: 18px;
          padding-right: 18px;
        }
      }
      .budget {
        width: 100%;
        display: flex;
        display: flex;
        align-items: center;
        align-content: center;
        justify-content: center;
        background: rgba(255, 255, 255, 0.18);
        p {
          color: #fff;
          text-align: center;
          font-family: Vollkorn;
          font-size: 17px;
          font-style: italic;
          font-weight: 400;
          line-height: 22px; /* 129.412% */
          //   padding: 18px 493px 17px 30px;
          padding-left: 18px;
          padding-right: 18px;
        }
      }
      .describe {
        width: 100%;
        display: flex;
        display: flex;
        align-items: center;
        align-content: center;
        justify-content: center;
        background: rgba(255, 255, 255, 0.2);
        p {
          display: flex;
          color: #fff;
          text-align: left;
          font-family: Vollkorn;
          font-size: 17px;
          font-style: italic;
          font-weight: 400;
          line-height: 22px; /* 129.412% */
          // padding: 17px 360px 88px 30px;
          padding-left: 18px;
          padding-right: 88px;
        }
      }
      .foot-btn {
        background-color: #000;
        color: #8bcac3;
        text-align: center;
        font-family: Vollkorn;
        font-size: 17px;
        font-style: italic;
        font-weight: 400;
        line-height: 22px; /* 129.412% */
        border-style: none;
        border: 1px solid #8bcac3;
        padding: 15px 60px 16px 60px;
        // padding-left: 15px;
        // padding-right: 15px;
        margin-top: 22px;
      }
    }
    .foot-img {
      width: 100%;
      display: flex;
      justify-content: center;
      flex-direction: column;
      align-items: center;
      img {
        width: 43px;
        height: 46px;
      }
      gap: 15px;
      p {
        color: rgba(255, 255, 255, 0.4);
        text-align: center;
        font-family: Vollkorn;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; /* 146.667% */
      }
    }
  }
}
@media (max-width: 770px) {
  .footer .foot-items {
    width: 100%;
  }
}
@media (max-width: 770px) {
  .footer .foot-items {
    width: 90%;
  }
}
</style>
