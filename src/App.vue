<template>
  <div>
    <navbar />
    <Process />
    <Brand />
    <Project />
    <Team />
    <Quotes />
    <Contact />
    <Footer />
  </div>
</template>

<script setup>
import navbar from "./components/Navbar.vue";
import Process from "@/components/ProcessComponent.vue";
import Brand from "./components/BrandComponent.vue";
import Project from "./components/ProjectsComponent.vue";
import Team from "./components/TeamComponent.vue";
import Quotes from "./components/QuotesComponents.vue";
import Contact from "./components/ContactComponent.vue";
import Footer from "./components/FootComponent.vue";
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Oswald&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Vollkorn&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  width: 940px;
  margin: 0 auto;
  // border: 1px solid rgb(0, 234, 255);
}
@media (max-width: 990px) {
  .container {
    width: 750px;
  }
}

@media (max-width: 770px) {
  .container {
    width: 520px;
  }
}
@media (max-width: 519px) {
  .container {
    width: 100%;
  }
}
</style>
