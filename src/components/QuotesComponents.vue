<template>
  <section class="quotes">
    <div class="container">
      <div class="quotes-items">
        <img src="../assets/note.png" alt="#" />
        <div class="quotes-text">
          <div class="text1">
            <p>
              “I love these guys! They did a great job. I would recommend them
              to anyone.”
            </p>
            <img src="../assets/photo_man.jpg" alt="#" />
            <h1>Julius Von Uberstien</h1>
          </div>
          <div class="text2">
            <p>“Elexis Corp. has grown immensely with the help of Minimal.”</p>
            <img src="../assets/photo_girl.jpg" alt="#" />
            <h1>Rachel Stamos</h1>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
.quotes {
  width: 100%;
  display: flex;
  align-items: center;
  align-content: center;
  justify-content: center;
  background: #f5f5f5;
  padding-bottom: 69px;
  padding-top: 69px;
  .quotes-items {
    width: 100%;
    display: flex;
    padding: 0.047px 23.5px 0px 23.5px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 36.953px;
    .quotes-text {
      width: 100%;
      display: flex;
      align-items: center;
      align-content: center;
      justify-content: center;
      display: flex;
      flex-wrap: wrap;
      padding-top: 30px;
      padding-bottom: 30px;

      .text1 {
        width: 50%;
        display: flex;
        align-items: center;
        align-content: center;
        justify-content: center;
        flex-direction: column;

        padding-left: 54px;
        padding-right: 54px;
        p {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 26px;
          font-style: normal;
          font-weight: 400;
          line-height: 33px; /* 126.923% */
        }
        img {
          margin-top: 24px;
          margin-bottom: 10px;
        }
        h1 {
          color: #ababab;
          text-align: center;
          font-family: Montserrat;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px; /* 142.857% */
          text-transform: uppercase;
        }
      }
      .text2 {
        width: 50%;
        display: flex;
        align-items: center;
        align-content: center;
        justify-content: center;
        flex-direction: column;
        border-left: 1px solid rgb(224, 223, 223);
        // padding-left: 54px;
        // padding-right: 54px;
        p {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 26px;
          font-style: normal;
          font-weight: 400;
          line-height: 33px; /* 126.923% */
        }
        img {
          margin-top: 24px;
          margin-bottom: 10px;
        }
        h1 {
          color: #ababab;
          text-align: center;
          font-family: Montserrat;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px; /* 142.857% */
          text-transform: uppercase;
        }
      }
    }
  }
}
@media (max-width: 770px) {
  .quotes .quotes-items .quotes-text .text1 {
    width: 100%;
    p {
      font-size: 20px;
    }
    margin-bottom: 15px;
  }
  .quotes .quotes-items .quotes-text .text2 {
    width: 100%;
    p {
      font-size: 20px;
    }
    border-top: 1px solid rgb(224, 223, 223);
    border-left: none;
    padding-top: 15px;
  }
}
</style>
