<template>
  <header>
    <nav>
      <ul>
        <li><NuxtLink to="/">Starting Page</NuxtLink></li>
        <li><NuxtLink  to="/games">Games</NuxtLink></li>
        <li><NuxtLink  to="/about">About</NuxtLink></li>
      </ul>
    </nav>
    </header>
</template>

<style scoped>
  header{
    width:100%;
    height:30px;
    display: flex;
    justify-content: center;
    align-items:center;
}

  ul{
    list-style: none;
    padding:0px;
    margin: 0px;
    display: flex;
    justify-content: center;
    align-items:center;
  }

  li{
    margin: 0px 10px;
  }
</style>
