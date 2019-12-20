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
        url: 'http://t.hotbootypics.com/thumbs/2014-04-23/44409_07.jpg',
        show: false
      },
      {
        id: 9,
        url: 'http://t.hotbootypics.com/nthumbs/2016-02-29/2313838/2313838_05.jpg',
        show: false
      },
      {
        id: 10,
        url: 'https://i.imgur.com/eZeGVk5.jpg',
        show: false
      },
      {
        id: 11,
        url: 'https://i.imgur.com/GHRpWr2.jpg',
        show: false
      },
      {
        id: 12,
        url: 'https://preview.redd.it/wms3wfd94s541.jpg?width=960&crop=smart&auto=webp&s=d0634c1dcef020404f52caa09c1c2f0571bf5247',
        show: false
      },
      {
        id: 13,
        url: 'https://i.imgur.com/iqfTJI0.jpg',
        show: false
      },
      {
        id: 14,
        url: 'https://i.imgur.com/68eilGT.png',
        show: false
      },
      {
        id: 15,
        url: 'https://preview.redd.it/3p5au0k0dt541.jpg?width=640&crop=smart&auto=webp&s=9fc3a5ee23011eb20eb48cda8a63da17e511cd0c',
        show: false
      },
      {
        id: 16,
        url: 'https://preview.redd.it/f2c7hha6pt541.jpg?width=640&crop=smart&auto=webp&s=c64414b2a9d02c291ed3a0a307b87ad4348d46fd',
        show: false
      },
      {
        id: 17,
        url: 'https://i.redd.it/1ysa9b9f9t541.jpg',
        show: false
      },
      {
        id: 18,
        url: 'https://i.imgur.com/2BGGEoJ.jpg',
        show: false
      },
      {
        id: 19,
        url: 'https://i.imgur.com/6n5vIeZ.jpg',
        show: false
      },
      {
        id: 20,
        url: 'https://i.redd.it/ms6er3ot8r541.jpg',
        show: false
      },
      {
        id: 21,
        url: 'https://i.redd.it/28x47vad7r541.png',
        show: false
      },
      {
        id: 22,
        url: 'https://i.redd.it/tne2ilbaxs541.jpg',
        show: false
      },
      {
        id: 23,
        url: 'https://i.imgur.com/WZJimaI.jpg',
        show: false
      },
      {
        id: 24,
        url: 'https://i.imgur.com/NjTjDMc.jpg',
        show: false
      },
      {
        id: 25,
        url: 'https://media.giphy.com/media/1266sbyhJZwgyk/giphy.gif',
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
