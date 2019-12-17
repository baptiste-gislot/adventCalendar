<template>
  <div id="app">
    <h1>The Booty Advent Calendar</h1>
    <DayList :days="days" />
  </div>
</template>

<script>
import DayList from './components/DayList';

export default {
  name: 'app',
  components: {
    DayList
  },
  data() {
    return {
      days: [{
        id: 1,
        url: 'http://cdn1.bigassphotos.com/92/e/92e8ec765.jpg',
        show: false
      },
      {
        id: 2,
        url: 'https://cdn.menprovement.com/wp-content/uploads/2017/07/38694f53aeb8b844a09146fff855d8a4.jpg',
        show: false
      },
      {
        id: 3,
        url: 'https://cdn.menprovement.com/wp-content/uploads/2017/07/best-ass-pictures.jpg',
        show: false
      },
      {
        id: 4,
        url: 'https://cdn.menprovement.com/wp-content/uploads/2013/12/ass-4.jpg',
        show: false
      },
      {
        id: 5,
        url: 'https://cdn.menprovement.com/wp-content/uploads/2017/07/ass2.jpg',
        show: false
      },
      {
        id: 6,
        url: 'https://cdn.menprovement.com/wp-content/uploads/2013/12/ass-8.jpg',
        show: false
      },
            {
        id: 7,
        url: 'https://cdn.menprovement.com/wp-content/uploads/2014/10/beautifu_butt.jpg',
        show: false
      },
      {
        id: 8,
        url: '',
        show: false
      },
      {
        id: 9,
        url: '',
        show: false
      },
      {
        id: 10,
        url: '',
        show: false
      },
      {
        id: 11,
        url: '',
        show: false
      },
      {
        id: 12,
        url: '',
        show: false
      },
      {
        id: 13,
        url: '',
        show: false
      },
      {
        id: 14,
        url: '',
        show: false
      },
      {
        id: 15,
        url: '',
        show: false
      },
      {
        id: 16,
        url: '',
        show: false
      },
      {
        id: 17,
        url: '',
        show: false
      },
      {
        id: 18,
        url: '',
        show: false
      },
      {
        id: 19,
        url: '',
        show: false
      },
      {
        id: 20,
        url: '',
        show: false
      },
      {
        id: 21,
        url: '',
        show: false
      },
      {
        id: 22,
        url: '',
        show: false
      },
      {
        id: 23,
        url: '',
        show: false
      },
      {
        id: 24,
        url: '',
        show: false
      },
      {
        id: 25,
        url: '',
        show: false
      }]
    }
  }
}
</script>

<style>
body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  background-image: url('https://cdn.jsdelivr.net/gh/kgolid/lukebilder@1ad5684/11/small/13.jpeg');
  background-size: cover;
  margin: 0;
  padding: 0;
  text-align: center;
  color: #7C4E8F;
  font-size: 60px;
}
</style>
