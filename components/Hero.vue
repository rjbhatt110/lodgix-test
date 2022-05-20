<template>
  <div class="background container-fluid">
    <div>
      <img src="/menu.png" alt="" />
    </div>
    <div
      class="d-flex flex-column justify-content-center align-items-center content"
    >
      <h1 class="text-center header">Vacation Rental Management Software</h1>
      <span class="font-weight-normal text-center sub-header">
        <h4>
          East-to-use, cost effective, vacation rental management software. No
          setup fees.
        </h4>
        <h4>
          No mandatory demos. No contracts. No credit card required. Free 30 day
          trial.
        </h4>
      </span>
      <b-button pill class="button"
        >START FREE TRIAL<i class="icon"></i
      ></b-button>
    </div>
    <b-carousel
      id="carousel-1"
      class="container"
      :interval="4000"
      controls
      indicators
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333"
    >
      <!-- v-model="slide" -->
      <!-- @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd" -->
      <b-carousel-slide img-src="/slide1.png"></b-carousel-slide>
      <b-carousel-slide img-src="/slide2.png"></b-carousel-slide>
      <b-carousel-slide img-src="/slide3.png"></b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  name: 'HeroSection',
}
</script>
<style>
.background {
  background: url(/Frame.png);
  background-size: cover;
  margin: 0;
  padding: 0;
}
.content {
  margin: 50px 0 0 0;
}
.header {
  color: #333333;
  font-weight: 900;
  margin-bottom: 25px;
}
.sub-header {
  margin-bottom: 25px;
}
</style>
