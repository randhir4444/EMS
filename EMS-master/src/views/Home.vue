<template>
  <div>
    <Carousel/>
    <Categories/>
    <FeatureEvents/>
  </div>
  
  
</template>

<script>
import Carousel from '../components/Carousel'
import Categories from '../components/Categories'
import FeatureEvents from '../components/FeatureEvents'

export default {
  components: {
    Carousel,
    Categories,
    FeatureEvents
  },
};
</script>

<style  scoped>

</style>
