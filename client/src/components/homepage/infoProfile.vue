<template>
<!-- column size = 8 -->
  <b-col cols="12" md="8">
    <b-card style="box-shadow: 2px 3px 3px 2px #f2f2f2">
      <b-media no-body>
        <b-media-aside cols="2" md="4">
          <b-img src="./static/mine2.jpg" width="128" height="256" alt="" />
        </b-media-aside>
        <br/>
        <b-media-body class="ml-3">
          <h2 class="mt-0">Who am i ?</h2>
          <p>
            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante
            sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis.
            Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis
            in faucibus.
          </p>
          <p class="mb-0">
            Donec sed odio dui. Nullam quis risus eget urna mollis ornare vel eu leo. Cum
            sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
          </p>
          <br/>
          <b-media>
          <b-img src="./static/logo1.png" width="64" alt="" class="flyinglogo"/>
            <h2 class="mt-2">What do i do?</h2>
              <p>Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue
              felis in faucibus.
              </p>
          </b-media>
        </b-media-body>
      </b-media>
    </b-card>
  </b-col>
</template>

<script>
export default {

}
</script>

<style scoped>
 .flyinglogo{
   position: fixed; z-index: 99; bottom:50px; right:25px;
 }
  p {
    font-size: 20px;
  }
</style>
