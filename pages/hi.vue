<template>
  <div>
    <div class="header-title">
      <h1>Suffering with Vue (tragic sounds*)</h1>
      <h2>Another tragic sound</h2>
    </div>
    <br>

    <div>
      <p>You wrote: {{ message }}</p>
      <input class="add-content" v-model="message" placeholder="Write something" />
    </div>
    <a @[eventName]="doSomething">Click here</a>
  </div>

</template>

<script>
export default {
  name: 'HiPage'
}
</script>

<style>
  .header-title{
    color:peru;
    font-family: 'Courier New', Courier, monospace;
  }

  .add-content{
    border-radius: 15px;
  }

  /* .color{
    color:black;
  } */

  .v-main{
    background: #dcd3e9;
  }
</style>
