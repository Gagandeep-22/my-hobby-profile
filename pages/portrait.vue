<template>
  <div class="text-center">
    <h2><u> My Drawings </u></h2>
    <div class="Portrait">
      <div class="singleImage" v-for="(image,i) in images" :key="i">
        <img :src="require(`../assets/Drawings/${image}.jpg`)" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked(i)">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes[i]}}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked(i)">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes[i] }}
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PortraitPage',
  data() {
    return {
      likes: [55, 4, 15, 25, 8, 50, 20, 10, 12, 60],
      dislikes: [0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
      lflag: [0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
      dflag: [0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
      images: ['1','2','3','4','5','6','7','8','9','10']
    }
  },
  methods: {
    liked(i) {
      console.log(i,"Entered Liked")
      if (this.lflag[i] == 0) {
        this.$set(this.likes,i,this.likes[i]+1)
        this.lflag[i] = 1
        console.log(this.likes,this.likes[i],this.lflag,"Entered clicked")
      } else {
        this.$set(this.likes,i,this.likes[i]-1)
        this.lflag[i] = 0
        console.log(i,"Entered disLiked")
      }
    },

    disliked(i) {
      if (this.dflag[i] == 0) {
        this.$set(this.dislikes,i,this.dislikes[i]+1)
        this.dflag[i] = 1
      } else {
        this.$set(this.dislikes,i,this.dislikes[i]-1)
        this.dflag[i] = 0
      }
    },
    
  },

}
</script>

<style scoped>
img {
  height: 200px;
  margin: 20px;
}

.Portrait {
  margin: 1rem;
  padding: 2rem 2rem;
  text-align: center;
}
.singleImage {
  display: inline-block;
  padding: 1rem 1rem;
  vertical-align: middle;
}
</style>
