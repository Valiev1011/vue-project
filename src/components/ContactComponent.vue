<template>
  <section class="contact">
    <div class="container">
      <div class="contact-items">
        <h1>LET’s Get in touch</h1>
        <hr />
        <div class="contact-infos">
          <div class="info1">
            <img src="../assets/location.png" alt="img" />
            <h1>MEET US IN PERSON</h1>
            <p>8776 Juniper Street</p>
            <p>Unit #204</p>
            <p>Merriweather, Ontorio</p>
            <p>Canada</p>
          </div>
          <div class="info1">
            <img src="../assets/message_bigger.png" alt="img" />
            <h1>The traditional way</h1>
            <p>Email us</p>
            <p>contact@minimal.com</p>
            <p>Contact form</p>
            <p>Scroll down</p>
          </div>
          <div class="info1">
            <img src="../assets/like.png" alt="img" />
            <h1>Let’s get social</h1>
            <span>
              <img src="../assets/IMAGE(20).png" alt="img" />
              <p>Facebook</p>
            </span>
            <span>
              <img src="../assets/twitter.png" alt="img" />
              <p>Twitter</p>
            </span>
            <span>
              <img src="../assets/linked-in.png" alt="img" />
              <p>Linkdin</p>
            </span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
.contact {
  width: 100%;
  // max-width: 1600px;
  // margin: auto auto;
  background: url("../assets/background-footer.jpg"),
    lightgray 50% / cover no-repeat;
  background-repeat: no-repeat;
  object-fit: cover;
  display: flex;
  background-size: cover;
  align-items: center;
  align-content: center;
  justify-content: center;
  background-position: center;
  padding-top: 69px;
  padding-bottom: 69px;
  .contact-items {
    width: 100%;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    h1 {
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
    .contact-infos {
      width: 100%;
      display: flex;
      padding-right: 0px;
      justify-content: center;
      flex-wrap: wrap;
      align-items: flex-start;
      flex-shrink: 0;
      .info1 {
        width: 33.3%;
        h1 {
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px; /* 125% */
          text-transform: uppercase;
          margin-top: 26px;
          margin-bottom: 20px;
        }
        p {
          color: #212121;
          text-align: center;
          font-family: Vollkorn;
          font-size: 17px;
          font-style: normal;
          font-weight: 400;
          line-height: 22px; /* 129.412% */
        }
        span {
          display: flex;
          // padding: 0px 119.953px 0px 0.047px;
          justify-content: center;
          align-items: center;
          align-content: center;
          gap: 9px;
          img {
            width: 14px;
            height: 14px;
          }
          p {
            color: #212121;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 20px; /* 117.647% */
            display: flex;
          }
        }
      }
    }
  }
}
@media (max-width: 770px) {
  .contact .contact-items .contact-infos .info1 {
    width: 100%;
    margin-bottom: 20px;
  }
}
</style>
