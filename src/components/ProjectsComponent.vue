<template>
  <section class="project">
    <div class="container">
      <div class="project-items">
        <h1>Recent projects</h1>
        <hr />
        <div class="project-row1">
          <div class="row1-col">
            <img src="../assets/img_1.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>woods</h1>
              <p>Photography</p>
            </div>
          </div>
          <div class="row1-col">
            <img src="../assets/img_2.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>path</h1>
              <p>Website</p>
            </div>
          </div>
          <div class="row1-col">
            <img src="../assets/img_3.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>darkness</h1>
              <p>Website</p>
            </div>
          </div>

          <div class="row1-col">
            <img src="../assets/img_4.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>waves</h1>
              <p>Photography</p>
            </div>
          </div>
          <div class="row1-col">
            <img src="../assets/img_5.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>drops</h1>
              <p>Website</p>
            </div>
          </div>
          <div class="row1-col">
            <img src="../assets/img_6.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>ocean</h1>
              <p>Website</p>
            </div>
          </div>

          <div class="row1-col">
            <img src="../assets/img_7.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>town</h1>
              <p>Website</p>
            </div>
          </div>
          <div class="row1-col">
            <img src="../assets/img_8.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>mountain</h1>
              <p>Website</p>
            </div>
          </div>
          <div class="row1-col">
            <img src="../assets/img_9.jpg" alt="#" />
            <div class="row1-col-text">
              <h1>camera</h1>
              <p>Website</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
.project {
  width: 100%;
  display: flex;
  align-items: center;
  align-content: center;
  justify-content: center;
  background-color: #f5f5f5;
  padding-top: 69px;
  padding-bottom: 69px;
  padding-left: 70px;
  padding-right: 70px;
  .project-items {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    align-content: center;
    justify-content: center;
    background-color: #f5f5f5;
    gap: 28;

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
    .project-row1 {
      width: 100%;
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
      .row1-col {
        width: calc(33% - 12px);
        display: flex;
        flex-direction: column;
        align-items: center;
        align-content: center;
        justify-content: center;
        flex-shrink: 0;

        img {
          width: 100%;
        }
        .row1-col-text {
          width: 100%;
          display: flex;
          align-items: center;
          align-content: center;
          justify-content: center;
          flex-direction: column;
          text-align: center;
          background-color: white;
          h1 {
            color: #333;
            text-align: center;
            font-family: Montserrat;
            font-size: 16px;
            font-style: normal;
            font-weight: 400;
            line-height: 20px; /* 125% */
            text-transform: uppercase;
            margin-top: 19px;
            margin-bottom: 4px;
          }
          p {
            color: #333;
            text-align: center;
            font-family: Vollkorn;
            font-size: 14px;
            font-style: normal;
            font-weight: 400;
            line-height: 20px; /* 142.857% */
            margin-bottom: 21px;
          }
        }
      }
    }
  }
}
@media (max-width: 770px) {
  .project .project-items .project-row1 .row1-col {
    width: calc(50% - 21px);
    margin: 0 auto;
  }
}
@media (max-width: 519px) {
  .project .project-items .project-row1 .row1-col {
    width: calc(100% - 21px);
    // width: 100%;
    margin: 0 auto;
  }
  .project {
    padding: 69px 20px;
  }
  .project .project-items hr {
    margin-bottom: 25px;
  }
}
</style>
