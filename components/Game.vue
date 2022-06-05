<template>
  <NuxtLink :to="'/games/' + id">
    <article class="game">
      <div class="pic" :style="{backgroundImage:'url(' + pic + ')'}"></div>
        <h1>{{title}}</h1>
        <p>{{description}} ID: {{id}}</p>

    </article>
  </NuxtLink>
</template>

<script>
  export default{
    props: ["pic", "title", "description", "id"]
  }
</script>

<style scoped>
  a{
    text-decoration:none;
    color: black;
  }
  .game{
      box-sizing: border-box;
      width: 280px;
      padding:8px;
      border: 1px solid #ccc;
      box-shadow: 0 2px 2px #aaa;
      margin: 10px;
    }

    .pic{
      background-position: center;
      background-size: cover;
      width: 100%;
      height: 200px;
    }
</style>
