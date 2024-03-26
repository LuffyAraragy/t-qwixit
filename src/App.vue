<template>
  <div class="app" id="app">
    <MainPage>
      
    </MainPage>
  </div>
</template>

<script>
import MainPage from './pages/MainPage.vue'

export default {
  name: 'App',
  components: {
    MainPage
  }
}
</script>

<style>

* {
  margin: 0;
  padding: 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

.text-title {
  /* color: #ffffff; */
  font-family: Unbounded;
  font-size: 24px;
  font-weight: 400;
  line-height: 40px;
  text-align: left;
  color: black;
}

.text {
  font-family: Raleway;
  font-size: 20px;
  font-weight: 500;
  line-height: 28px;
  text-align: left;
  /* color: #ffffff; */
  color: black;
}

.text--green {
  color: #9ECD31;
}

.block-content {
  display: grid;
  gap: 32px;
}

.button {
  width: 100%;
  padding: 12px 24px;
  max-width: 210px;
  height: 52px;
  background-color: #ffffff;
  border: #B8FF14 solid 2px;
}

</style>
