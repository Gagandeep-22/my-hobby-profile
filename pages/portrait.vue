<template>
  <div class="text-center">
    <h2><u> My Drawings </u></h2>
    <div class="Portrait">
      <div class="singleImage">
        <img src="../assets/Drawings/1.jpg" />
        <div>
          <v-btn
            class="ma-2"
            text
            icon
            color="blue lighten-2"
            @click="liked1()"
           >
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes1 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked1()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes1 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/2.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked2()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes2 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked2()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes2 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/3.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked3()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes3 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked3()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes3 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/4.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked4()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes4 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked4()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes4 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/5.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked5()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes5 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked5()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes5 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/6.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked6()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes6 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked6()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes6 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/7.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked7()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes7 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked7()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes7 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/8.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked8()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes8 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked8()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes8 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/9.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked9()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes9 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked9()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes9 }}
        </div>
      </div>
      <div class="singleImage">
        <img src="../assets/Drawings/10.jpg" />
        <div>
          <v-btn class="ma-2" text icon color="blue lighten-2" @click="liked10()">
            <v-icon>mdi-thumb-up</v-icon>
          </v-btn>
          {{ likes10 }}
          <v-btn class="ma-2" text icon color="red lighten-2" @click="disliked10()">
            <v-icon>mdi-thumb-down</v-icon>
          </v-btn>
          {{ dislikes10 }}
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
      likes1: 0,
      dislikes1: 0,
      likes2: 0,
      dislikes2: 0,
      likes3: 0,
      dislikes3: 0,
      likes4: 0,
      dislikes4: 0,
      likes5: 0,
      dislikes5: 0,
      likes6: 0,
      dislikes6: 0,
      likes7: 0,
      dislikes7: 0,
      likes8: 0,
      dislikes8: 0,
      likes9: 0,
      dislikes9: 0,
      likes10: 0,
      dislikes10: 0,
      lflag1: 0,
      lflag2: 0,
      lflag3: 0,
      lflag4: 0,
      lflag5: 0,
      lflag6: 0,
      lflag7: 0,
      lflag8: 0,
      lflag9: 0,
      lflag10: 0,
      dflag1: 0,
      dflag2: 0,
      dflag3: 0,
      dflag4: 0,
      dflag5: 0,
      dflag6: 0,
      dflag7: 0,
      dflag8: 0,
      dflag9: 0,
      dflag10: 0,
    }
  },
  methods: {
    liked1() {
      if (this.lflag1 == 0) {
        this.likes1++
        this.lflag1 = 1
      } else {
        this.likes1--
        this.lflag1 = 0
      }
    },

    disliked1() {
      if (this.dflag1 == 0) {
        this.dislikes1++
        this.dflag1 = 1
      } else {
        this.dislikes1--
        this.dflag1 = 0
      }
    },

    liked2() {
      if (this.lflag2 == 0) {
        this.likes2++
        this.lflag2 = 1
      } else {
        this.likes2--
        this.lflag2 = 0
      }
    },

    disliked2() {
      if (this.dflag2 == 0) {
        this.dislikes2++
        this.dflag2 = 2
      } else {
        this.dislikes2--
        this.dflag2 = 0
      }
    },

    liked3() {
      if (this.lflag3 == 0) {
        this.likes3++
        this.lflag3 = 3
      } else {
        this.likes3--
        this.lflag3 = 0
      }
    },

    disliked3() {
      if (this.dflag3 == 0) {
        this.dislikes3++
        this.dflag3 = 3
      } else {
        this.dislikes3--
        this.dflag3 = 0
      }
    },

    liked4() {
      if (this.lflag4 == 0) {
        this.likes4++
        this.lflag4 = 4
      } else {
        this.likes4--
        this.lflag4 = 0
      }
    },

    disliked4() {
      if (this.dflag4 == 0) {
        this.dislikes4++
        this.dflag4 = 4
      } else {
        this.dislikes4--
        this.dflag4 = 0
      }
    },

    liked5() {
      if (this.lflag5 == 0) {
        this.likes5++
        this.lflag5 = 5
      } else {
        this.likes5--
        this.lflag5 = 0
      }
    },

    disliked5() {
      if (this.dflag5 == 0) {
        this.dislikes5++
        this.dflag5 = 5
      } else {
        this.dislikes5--
        this.dflag5 = 0
      }
    },

    liked6() {
      if (this.lflag6 == 0) {
        this.likes6++
        this.lflag6 = 6
      } else {
        this.likes6--
        this.lflag6 = 0
      }
    },

    disliked6() {
      if (this.dflag6 == 0) {
        this.dislikes6++
        this.dflag6 = 6
      } else {
        this.dislikes6--
        this.dflag6 = 0
      }
    },

    liked7() {
      if (this.lflag7 == 0) {
        this.likes7++
        this.lflag7 = 7
      } else {
        this.likes7--
        this.lflag7 = 0
      }
    },

    disliked7() {
      if (this.dflag7 == 0) {
        this.dislikes7++
        this.dflag7 = 7
      } else {
        this.dislikes7--
        this.dflag7 = 0
      }
    },

    liked8() {
      if (this.lflag8 == 0) {
        this.likes8++
        this.lflag8 = 8
      } else {
        this.likes8--
        this.lflag8 = 0
      }
    },

    disliked8() {
      if (this.dflag8 == 0) {
        this.dislikes8++
        this.dflag8 = 8
      } else {
        this.dislikes8--
        this.dflag8 = 0
      }
    },

    liked9() {
      if (this.lflag9 == 0) {
        this.likes9++
        this.lflag9 = 9
      } else {
        this.likes9--
        this.lflag9 = 0
      }
    },

    disliked9() {
      if (this.dflag9 == 0) {
        this.dislikes9++
        this.dflag9 = 9
      } else {
        this.dislikes9--
        this.dflag9 = 0
      }
    },

    liked10() {
      if (this.lflag10 == 0) {
        this.likes10++
        this.lflag10 = 10
      } else {
        this.likes10--
        this.lflag10 = 0
      }
    },

    disliked10() {
      if (this.dflag10 == 0) {
        this.dislikes10++
        this.dflag10 = 10
      } else {
        this.dislikes10--
        this.dflag10 = 0
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
