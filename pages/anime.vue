<template>
  <div class="text-center">
    <h2><u>Favouite Animes </u></h2>
    <div class="Parent">
        <div v-for="(anime, i) in AnimeList" :key="i" class="child">
          <a :href="anime.link">
            <img :src="require(`../assets/Anime/${anime.pic}.jpg`)"/>
            <h3>{{ anime.name }}</h3></a
          >
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'InspirePage',
  data() {
    return {
      AnimeList: [
        {
          pic: 'Naruto',
          name: 'Naruto',
          link: 'https://www.imdb.com/title/tt0409591/',
        },
        {
          pic: 'OnePiece',
          name: 'One Piece',
          link: 'https://www.imdb.com/title/tt0388629/?ref_=nv_sr_srsg_7',
        },
        {
          pic: 'Violet',
          name: 'Violet Evergarden',
          link: 'https://www.imdb.com/title/tt7078180/?ref_=nv_sr_srsg_0',
        },
        {
          pic: 'Steins',
          name: 'Steins;Gate',
          link: 'https://www.imdb.com/title/tt1910272/?ref_=nv_sr_srsg_0',
        },
        {
          pic: 'BluePeriod',
          name: 'Blue Period',
          link: 'https://www.imdb.com/title/tt14115912/?ref_=nv_sr_srsg_0',
        },
        {
          pic: 'YourLieInApril',
          name: 'Your Lie in April',
          link: 'https://www.imdb.com/title/tt3895150/?ref_=nv_sr_srsg_0',
        },
        {
          pic: 'BlackClover',
          name: 'Black Clover',
          link: 'https://www.imdb.com/title/tt7441658/?ref_=nv_sr_srsg_0',
        },
      ],
    }
  },
}
</script>


<style scoped>
img {
  height: 200px;
  margin: 20px;
}

.Parent {
  margin: 1rem;
  padding: 2rem 2rem;
  text-align: center;
}
.child,
a {
  display: inline-block;
  padding: 1rem 1rem;
  vertical-align: middle;
  text-decoration: none;
  color: white;
}

a:hover {
  text-decoration: underline;
  color: rgb(177, 129, 221);
}
</style>