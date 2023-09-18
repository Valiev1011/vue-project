<template>
  <section class="team">
    <div class="container">
      <div class="team-items">
        <h1>our team</h1>
        <hr />
        <div class="team-main">
          <div class="team-card1">
            <img src="../assets/person_1.jpg" alt="#" class="immgg" />
            <h1>Ron Swanson</h1>
            <p>Founder</p>
            <div class="team-icons">
              <img src="../assets/twitter.png" alt="#" />
              <img src="../assets/linked-in.png" alt="#" />
              <img src="../assets/message.png" alt="#" />
            </div>
          </div>
          <div class="team-card1">
            <img src="../assets/person_2.png" alt="#" class="images" />
            <h1>Julia Depish</h1>
            <p>Marketing</p>
            <div class="team-icons">
              <img src="../assets/twitter.png" alt="#" />
              <img src="../assets/linked-in.png" alt="#" />
              <img src="../assets/message.png" alt="#" />
            </div>
          </div>
          <div class="team-card1">
            <img src="../assets/person_3.jpg" alt="#" />
            <h1>Danny Devry</h1>
            <p>Designer</p>
            <div class="team-icons">
              <img src="../assets/twitter.png" alt="#" />
              <img src="../assets/linked-in.png" alt="#" />
              <img src="../assets/message.png" alt="#" />
            </div>
          </div>
          <div class="team-card1">
            <img src="../assets/person_4.jpg" alt="#" />
            <h1>Lisa Smith</h1>
            <p>Developer</p>
            <div class="team-icons">
              <img src="../assets/twitter.png" alt="#" />
              <img src="../assets/linked-in.png" alt="#" />
              <img src="../assets/message.png" alt="#" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
.team {
  width: 100%;
  display: flex;
  align-items: center;
  align-content: center;
  justify-content: center;
  padding-top: 69px;
  padding-bottom: 69px;
  .team-items {
    width: 100%;
    display: flex;
    align-items: center;
    align-content: center;
    justify-content: center;
    flex-direction: column;
    padding-bottom: 20px;
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
    .team-main {
      width: 100%;
      display: flex;
      align-items: center;
      align-content: center;
      flex-wrap: wrap;
      justify-content: center;
      flex-shrink: 0;

      .team-card1 {
        width: 24.5%;
        display: flex;
        align-items: center;
        align-content: center;
        justify-content: center;
        flex-direction: column;
        padding-left: 10px;
        padding-right: 10px;
        img {
          width: 100%;
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
          margin-top: 20px;
          margin-bottom: 6px;
        }
        p {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px; /* 142.857% */
          margin-bottom: 18px;
        }
        .team-icons {
          display: flex;
          // padding: 11.047px 60px 9.953px 61px;
          padding-top: 11.047px;
          padding-bottom: 9.953px;
          justify-content: center;
          align-content: center;
          align-items: flex-start;
          gap: 6px;
          flex-shrink: 0;
          img {
            background-color: #f5f5f5;
            padding-left: 8px;
            padding-right: 8px;
          }
        }
      }
    }
  }
}
@media (max-width: 770px) {
  .team .team-items .team-main .team-card1 {
    width: 50%;
    margin-top: 15px;
  }
}
@media (max-width: 519px) {
  .team .team-items .team-main .team-card1 {
    width: 90%;
    margin-top: 15px;
  }
}
</style>
