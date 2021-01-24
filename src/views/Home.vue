<template>
  <div class="home">
    <HeaderShayna />
    <HeroBanner />
    <WomenBanner />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroBanner from "@/components/HeroBanner.vue";
import WomenBanner from "@/components/WomenBanner.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerShayna from "@/components/PartnerShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroBanner,
    WomenBanner,
    InstaShayna,
    PartnerShayna,
    FooterShayna,
  },
};
</script>
