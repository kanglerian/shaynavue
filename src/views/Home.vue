<template>
  <div class="home">
    <HeaderShayna/>
    <HeroBanner/>
    <WomenBanner/>
  </div>
</template>

<script>

import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroBanner from '@/components/HeroBanner.vue';
import WomenBanner from '@/components/WomenBanner';

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroBanner,
    WomenBanner
  }
}
</script>
