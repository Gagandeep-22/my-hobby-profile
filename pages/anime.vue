<template>
  <div class="text-center">
    <h2><u>Favouite Animes </u></h2>
    <div class="Parent">
        <a href="https://www.imdb.com/title/tt0409591/">
          <img src="../assets/Anime/Naruto.jpg"
        /><h3>Naruto</h3></a>
        <a href="https://www.imdb.com/title/tt0388629/?ref_=nv_sr_srsg_7">
          <img src="../assets/Anime/OnePiece.jpg"
        /><h3>One Piece</h3></a>
        <a href="https://www.imdb.com/title/tt7078180/?ref_=nv_sr_srsg_0">
          <img src="../assets/Anime/Violet.jpg"
        /><h3>Violet Evergarden</h3></a>
        <a href="https://www.imdb.com/title/tt1910272/?ref_=nv_sr_srsg_0">
          <img src="../assets/Anime/Steins.jpg"
        /><h3>Steins;Gate</h3></a>
        <a href="https://www.imdb.com/title/tt14115912/?ref_=nv_sr_srsg_0">
          <img src="../assets/Anime/BluePeriod.jpg"
        /><h3>BluePeriod</h3></a>
        <a href="https://www.imdb.com/title/tt3895150/?ref_=nv_sr_srsg_0">
          <img src="../assets/Anime/YourLieInApril.jpg"
        /><h3>Your Lie in April</h3></a>
        <a href="https://www.imdb.com/title/tt7441658/?ref_=nv_sr_srsg_0">
          <img src="../assets/Anime/BlackClover.jpg"
        /><h3>Black Clover</h3></a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'InspirePage',
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