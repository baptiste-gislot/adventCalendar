<template>
  <div class="container" @click="isClickable()">
    <div v-bind:key="day.id" v-for="day in days">
      <Day :day="day" v-bind:class="{notClickable : isClickable(day.id)}" />
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
  props: ["days"],
  data() {
    return {
      not_Clickable: false,
    }
  },
  methods: {
    isClickable(day) {
      let date = new Date();
      let numOfTOday = String(date.getDate()).padStart(2, '0');
      if (day < numOfTOday) {
        return false;
      } else {
        return true;
      }
    }
  }
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}

.notClickable {
  pointer-events: none;
}
</style>