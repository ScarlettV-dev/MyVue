<template>
  <section class="single-game">
    <h1>{{ $route.params.id }}</h1>
    <h1>{{ $route.params.name }}</h1>
    <div>
      <img src="">
    </div>
    <p>Deeper game description</p>
  </section>
  <!-- <p>{{ $route.params.id }}</p> -->
</template>

<style scoped>
  .single-game{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-flow: column;
    text-align: center;
    padding: 30px;
  }
</style>
