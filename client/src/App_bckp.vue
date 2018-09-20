<template>
<div id="App">
  <topbar></topbar>
  <navbar></navbar>
<br/>
<router-view/>
</div>
</template>

<script>
import navbar from './components/navbar/index'
import topbar from './components/navbar/topbar'

export default {
  name: 'App',

  components: {
    navbar, 
    topbar
  }
  
}
</script>

<style>
  h1, h2, h3, h4, h5, h6, b, strong {
    font-family: 'Fredoka One', cursive;
  }
  p {
    font-family: 'Quicksand', sans-serif;
  }
  div, ul, li, a {
    font-family: 'Cabin', sans-serif;
  }

</style>
