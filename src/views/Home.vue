<template>
  <div class="home">

    <HeaderDomn />

    <HeroDomn/>

    <BannerDomn/>

    <InstaDomn/>

    <PartnerDomn/>

    <FooterDomn/>

  </div>
</template>

<script>
  import HeaderDomn from '@/components/HeaderDomn.vue';
  import HeroDomn from '@/components/HeroDomn.vue';
  import BannerDomn from '@/components/BannerDomn.vue';
  import InstaDomn from '@/components/InstaDomn.vue';
  import PartnerDomn from '@/components/PartnerDomn.vue';
  import FooterDomn from '@/components/FooterDomn.vue';

  export default {
    name: 'Home',
    components: {
      HeaderDomn,
      HeroDomn,
      BannerDomn,
      InstaDomn,
      PartnerDomn,
      FooterDomn
    }
  }
</script>