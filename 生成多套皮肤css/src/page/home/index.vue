<template>
  <div class="wrapper page-home">
    <m-header></m-header>
    <m-recommend></m-recommend>
  </div>
</template>
<script>
import Header from "../../components/m-header/m-header";
import Recommend from "./components/recommend";
export default {
  name: "index",
  data() {
    return {};
  },
  components: {
    "m-header": Header,
    "m-recommend": Recommend,
  },
};
</script>
