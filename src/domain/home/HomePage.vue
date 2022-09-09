<template>
  <div class="home">
    <div>
      <img class="hr-training" src="../../assets/hr-training.jpg" aria-hidden="true" />
    </div>
  </div>
  <div>
    <a href="">Create your first workout!</a>
  </div>
  <Workout />
</template>

<script>
import Workout from '../workout/workout.vue';

export default {
  // Name of the component
  name: 'HomePage',
  components: {
    Workout,
  },
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
