<template>
  <div>
    <b-carousel id="carousel-fade" v-model="slide" :interval="2000" style="text-shadow: 0px 0px 2px #000" fade
      indicators img-width="1024" img-height="400" @sliding-start="onSlideStart" @sliding-end="onSlideEnd">
      <b-carousel-slide caption="First Slide" img-src="https://picsum.photos/1024/400/?image=10"></b-carousel-slide>
      <b-carousel-slide caption="Second Slide" img-src="https://picsum.photos/1024/400/?image=12"></b-carousel-slide>
      <b-carousel-slide caption="Third Slide" img-src="https://picsum.photos/1024/400/?image=22"></b-carousel-slide>
    </b-carousel>
  </div>
</template>


<script>

export default {
  name: 'HomeView',
  components: {

  }
}
</script>
