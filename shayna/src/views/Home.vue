<template>
  <div class="home">
    <HeaderShayna />
    <HeroSection />
    <WomenBanner />
    <InstaBanner />
    <PartnerLogo />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroSection from '@/components/HeroSection.vue';
import WomenBanner from '@/components/WomenBanner.vue';
import InstaBanner from '@/components/InstaBanner.vue';
import PartnerLogo from '@/components/PartnerLogo.vue';
import FooterShayna from '@/components/FooterShayna.vue';




export default {
  name: 'Home',
  components: {
    // HelloWorld
    HeaderShayna,
    HeroSection,
    WomenBanner,
    InstaBanner,
    PartnerLogo,
    FooterShayna
  }
}
</script>
