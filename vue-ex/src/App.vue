<template>
  <div className="home">
    <MainHeader/>
    <MainProducts/>
    <MainCompany/>
    <MainPricing/>
    <MainFooter/>
  </div>
</template>

<script>
import MainHeader from "./components/MainHeader.vue";
import MainProducts from "./components/MainProducts.vue";
import MainCompany from "./components/MainCompany.vue";
import MainPricing from "./components/MainPricing.vue";
import MainFooter from "./components/MainFooter.vue";

export default {
  name: "App",
  components: {
    MainHeader,
    MainProducts,
    MainCompany,
    MainPricing,
    MainFooter
  }
};
</script>

<style>

</style>
