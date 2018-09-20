<template>
<div id="App">
  <router-view/>
</div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  h1, h2, h3, h4, h5, h6, b, strong {
    font-family: 'Fredoka One', cursive;
    color: #777
  }
  p {
    font-family: 'Quicksand', sans-serif;
  }
  div, ul, li, a {
    font-family: 'Cabin', sans-serif;
  }
  #App {
    margin-top: 50px
  }
  body{
    background: #566670
  }
</style>
