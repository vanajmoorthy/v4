<template>
  <div class="home">
    <div class="container">
      <div class="column1">
        <div class="content">
          <h1>Hi, I'm Vanaj Moorthy!</h1>
          <h2>
            I'm an 18 year old developer and artist from New Delhi.
          </h2>
          <img id="scooter2" src="../assets/scooter.svg" alt="scooter image" />
          <h3>
            I'm an avid front-end web developer, a backend novice, and
            proficient digital artist. I enjoy making mostly inane but sometimes
            useful web projects and I love (3D) art and motion graphics.
          </h3>
        </div>
      </div>
      <div class="column2">
        <div class="imgcontainer">
          <img id="scooter" src="../assets/scooter.svg" alt="scooter image" />
        </div>
      </div>
    </div>

    <Footer></Footer>
  </div>
</template>

<script>
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Footer
  }
};
</script>

<style scoped>
h1 {
  font-weight: 600;
  color: #576980;
  font-size: 38px;
}

h2 {
  font-weight: 500;
  color: #7f8c9c;
  width: 60%;
  font-size: 28px;
}

h3 {
  font-weight: 400;
  color: #576980;
  width: 80%;
  font-size: 22px;
  line-height: 24px;
}

.home {
  font-family: canada-type-gibson, sans-serif;
  font-style: normal;
  display: flex;
  min-height: calc(100vh - 9vh - 40px - 0.8em);
  flex-direction: column;
}

.container {
  padding-left: 2rem;
  padding-right: 2rem;
  flex: 1;
  display: flex;
  height: calc(100vh - 13vh - 9vh);
}

.column1,
.column2 {
  margin: auto;
  width: 50%;
}

.column2 {
  text-align: center;
}

#scooter {
  width: 32rem;
  margin: auto;
  padding-bottom: 60px;
}

#scooter2 {
  width: 24rem;
  margin: auto;
  padding-bottom: 60px;
  display: none;
}

@media only screen and (max-width: 1052px) {
  #scooter {
    width: 28rem;
  }
}

@media only screen and (max-width: 920px) {
  .column2 {
    display: none;
  }
  .column1 {
    text-align: center;
    width: auto;
  }

  h2,
  h3 {
    width: auto;
  }

  h1 {
    font-size: 28px;
  }

  h2 {
    font-size: 24px;
  }

  h3 {
    font-size: 22px;
  }

  #scooter2 {
    display: block;
  }
}

@media only screen and (max-width: 506px) {
  #scooter2 {
    width: 22rem;
  }
}

@media only screen and (max-width: 414px) {
  #scooter2 {
    width: 20rem;
  }
}

@media only screen and (max-width: 375px) {
  #scooter2 {
    width: 18rem;
  }
}

@media only screen and (max-width: 320px) {
  #scooter2 {
    width: 14rem;
  }
}
</style>
