<template>
  <div
    v-editable="blok"
    class="py-8 mb-6 text-5xl font-bold text-center">
    <!--<carousel>
      <slide>
        Slide 1 Content
      </slide>
      <slide>
        Slide 2 Content
      </slide>
    </carousel>-->
  </div>
</template>
 
<script>
//import { Carousel, Slide } from 'vue-carousel';

export default {
  props: {
    blok: {
      type: Object,
      required: true
    }
  },
  /*components: {
    Carousel,
    Slide
  },*/
}
</script>