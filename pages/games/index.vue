<template>
  <section class="pc-games">
   <Game
     pic="https://www.gamespot.com/a/uploads/scale_landscape/1587/15875866/3578797-borderlands-3-review-thumb-nologo.jpg"
     title="Borderlands 3"
     id="1"
     description="First Person Shooter"/>

     <Game
     pic="https://www.google.com/imgres?imgurl=https%3A%2F%2Fs3.amazonaws.com%2Fprod-media.gameinformer.com%2Fstyles%2Fthumbnail%2Fs3%2Flegacy-images%2FBeauty%2520In%2520Death%2Foriandblindforesthero.jpg&imgrefurl=https%3A%2F%2Fwww.gameinformer.com%2Fgames%2Fori_and_the_blind_forest%2Fb%2Fxboxone%2Farchive%2F2015%2F03%2F09%2Fbeauty-in-death.aspx&tbnid=YK8RzEY49ynBcM&vet=12ahUKEwiW9ZHU65b4AhWRs3IEHQODC2EQMygNegUIARDXAQ..i&docid=3dOvlWhQaU9yWM&w=800&h=450&q=ori%20and%20the%20blind%20forest&hl=es-419&ved=2ahUKEwiW9ZHU65b4AhWRs3IEHQODC2EQMygNegUIARDXAQ"
     title="Ori and the Blind Forest"
     id="2"
     description="Adventure Game"/>

     <Game
     pic="https://www.google.com/imgres?imgurl=https%3A%2F%2Fmiketendo64.com%2Fwp-content%2Fuploads%2F2019%2F04%2FH2x1_NSwitchDS_Cuphead_image1600w.jpg&imgrefurl=https%3A%2F%2Fmiketendo64.com%2F2019%2F04%2F18%2Fswitch-review-cuphead%2F&tbnid=zxFzpkMmuUBH0M&vet=12ahUKEwixybeA75b4AhXho3IEHUo0BzwQMygOegUIARD4AQ..i&docid=QsKC8NdsEUYHGM&w=1600&h=800&q=cuphead&ved=2ahUKEwixybeA75b4AhXho3IEHUo0BzwQMygOegUIARD4AQ"
     title="Cuphead"
     id="3"
     description="Adventure Game"/>

     <Game
     pic="https://www.google.com/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fen%2F7%2F7f%2FSims4_Rebrand.png&imgrefurl=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FThe_Sims_4&tbnid=NRlYhzhtIfN1AM&vet=12ahUKEwitn-am75b4AhXvrHIEHRX2DWkQMygDegUIARDfAQ..i&docid=jxctw9qHOXVAJM&w=258&h=387&q=sims%204&ved=2ahUKEwitn-am75b4AhXvrHIEHRX2DWkQMygDegUIARDfAQ"
     title="The Sims 4"
     id="4"
     description="Social Simulation"/>

  </section>
</template>

<script>
  import Game from '@/components/Game'

  export default{
    components:{
      Game
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
