<template>
  <div class="home">   
    <HeaderToko />
    <Carousel />
    <CarouselItem/>
    <InstaToko />
    <Partner/>
    <FooterToko/>
    </div>
</template>

<script>
// @ is an alias to /src
import HeaderToko from '@/components/HeaderToko.vue'
import Carousel from '@/components/Carousel.vue'
import CarouselItem from '@/components/CarouselItem.vue'
import InstaToko from '@/components/InstaToko.vue'
import Partner from '@/components/Partner.vue'
import FooterToko from '@/components/FooterToko.vue'
export default {
  name: 'home',
  components: {
    HeaderToko,
    Carousel,
    CarouselItem,
    InstaToko,
    Partner,
    FooterToko
  }
}
</script>
