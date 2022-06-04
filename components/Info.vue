<template>
  <div class="text-center container">
      <div>
    <v-btn rounded dark @click="toAnime()"> Animes </v-btn>
    </div>
    <div>
    <v-btn rounded dark @click="toPortrait()"> Portraits </v-btn>
  </div>
  </div>
</template>


<style scoped>
.container {
  display: block;
  position: relative;
  margin: auto;
  width: 100%;
  text-align: center;
  padding: 20px;
}

.container div {
    display: block;
    position: relative;
    padding: 20px;
}
</style>


<script>
export default {
  methods: {
    toAnime() {
      this.$router.push('/anime');
    },
    toPortrait() {
      this.$router.push('/portrait');
    },
  },
}
</script>