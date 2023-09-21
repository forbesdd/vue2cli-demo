<template>
  <div class="App">
    <!-- header -->
    <HmHeader></HmHeader>
    <!-- main -->

    <HmMain></HmMain>
    <!-- footer -->
    <HmFooter></HmFooter>
  </div>
</template>

<script>
import HmFooter from './components/HmFooter.vue'
import HmHeader from './components/HmHeader.vue'
import HmMain from './components/HmMain.vue'
export default {
  components: { HmHeader, HmMain, HmFooter },

}
</script>

<style>
.App {
  width: 600px;
  height: 700px;
  background-color: #87ceeb;
  margin: 0 auto;
  padding: 20px;
}
</style>