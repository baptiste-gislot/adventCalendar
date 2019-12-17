<template>
  <div class="container">
    <div v-bind:key="day.id" v-for="day in days">
      <Day :day="day" />
    </div>
  </div>
</template>

<script>
import Day from './Day';

export default {
  name: "DayList",
  components: {
    Day
  },
  props: ["days"]
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}
</style>