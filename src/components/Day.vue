<template>
  <div class="day_cover">
    <h1 v-if="day.show === false">{{day.id}}</h1>
    <img v-on:click="handleClick" v-bind:src="$data[day.show ? 'toShow' : 'cover']"/>
  </div>
</template>

<script>
export default {
  name: "Day",
  props: ["day"],
  data() {
    return {
      cover: 'https://cdn.jsdelivr.net/gh/kgolid/lukebilder@1ad5684/11/small/04.jpeg',
      toShow: ''
    }
  },
  methods: {
    handleClick() {
      this.toShow = this.day.url;
      this.day.show = !this.day.show;
    }
  }
}
</script>

<style scoped>
.day_cover {
  height: 300px;
  width: 300px;
  border: 2px solid black;
  margin: 50px;
  text-align: center;
  font-size: 60px;
}

img {
  height: 300px;
  width: 300px;
}

h1 {
  position: absolute;
  padding-left: 120px;
}
</style>