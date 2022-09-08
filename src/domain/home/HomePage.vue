<template>
  <div class="home">
    <div>
      <img class="hr-training" src="../../assets/hr-training.jpg" aria-hidden="true" />
    </div>
    <div>
      <a href="">Create your first workout!</a>
    </div>
  </div>
</template>

<script>
export default {
  // Name of the component
  name: 'HomePage',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  text-align: center;
}

.hr-training {
  height: 300px;
}
</style>
