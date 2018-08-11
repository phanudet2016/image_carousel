<template>
  <div class="hello">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active" style="color:red"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img class="d-block w-100" src="https://www.music-man.com/assets/images/iconic-design-bg.jpg.pagespeed.ce.BA2MWIrBe9.jpg" alt="First slide" width="800" height="470">
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="https://www.music-man.com/assets/images/basses-header-desktop.jpg.pagespeed.ce.GOHtzT-YFb.jpg" alt="Second slide" width="1145" height="470">
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="https://www.music-man.com/assets/images/guitars-header-desktop.jpg.pagespeed.ce.pXxiWC7q7G.jpg" alt="Third slide" width="1145" height="470">
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="https://s3-us-west-2.amazonaws.com/static.music-man.com/website/images/instruments/desktop_header/full/3.jpg?1516317589" alt="Third slide" width="1145" height="470">
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
