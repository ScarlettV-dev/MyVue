<template>
  <section class="pc-games">
    <v-btn @click="add" class="error">ADD</v-btn>

   <Game v-for="(game,index) in games"
     :pic="game.pic"
     :title="game.title"
     :id="index"
     :description="game.description"
     :key="index" />


    

  </section>
</template>

<script>
  import Game from '@/components/Game'

  export default{
    components:{
      Game
    },
    data() {
      return {
        games: [
          {pic:"https://media.contentapi.ea.com/content/dam/eacom/SIMS/common/ts4-hero-marge-220325-ftue-base-game-xl.jpg.adapt.1920w.jpg",title:"The Sims 4", description:"Social Simulation"},
          {pic:"cuphead.png",title:"Cuphead", description:"Adventure Game"},
          {pic:"ori.jpeg",title:"Ori and the Blind Forest", description:"Adventure Game"},
          {pic:"https://www.gamespot.com/a/uploads/scale_landscape/1587/15875866/3578797-borderlands-3-review-thumb-nologo.jpg",title:"Borderlands 3", description:"First Person Shooter"}
        ]
      }
    },
    methods: {
      add: function() {
        this.games.push(
          {pic:"ori.jpeg",title:"Ori and the Blind Forest", description:"Adventure Game"},

        )
      }
    }
  }
</script>

<style scoped>
  .pc-games{
    display:flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
  }

</style>
