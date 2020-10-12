<template>
  <div>
    <section class="section">
      <div class="container-fliud">
        <img alt="Vue logo" class="rounded-circle" :src="tanuprofilepic" />
        <h1>Software Developer</h1>
        <p>This is a fun project I built while learning vue.js and bootstrap</p>
        <button type="button" class="btn btn-primary btn-lg">Contact</button>
      </div>
    </section>
  </div>
</template>
<script>
import tanuprofilepic from "../assets/tanuVueProfile.jpg";
export default {
  data: function () {
    return {
      tanuprofilepic: tanuprofilepic,
    };
  },
};
</script>
<style lang="css" scoped>
.section {
  padding-top: 10%;
  padding-bottom: 10%;
}
.rounded-circle {
  border-radius: 50% !important;
  width: 200px;
  height: 200px;
}
h1 {
  color: red;
}
p {
  color: black;
}
</style>