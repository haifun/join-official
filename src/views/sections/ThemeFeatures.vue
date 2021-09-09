<template>
  <base-section id="theme-features">
    <base-section-heading title="PRODUCTS">
      GXChain is a fundamental blockchain for the global data economy, designed to build a trusted data internet of value.
Benefiting from DPoS based Graphene underlying architecture, GXChain possesses functions including G-ID, GVM, BaaS and Blockcity, which are convenient for application development. GXChain based DApp-Blockcity has more than two million verified users and provides abundant data for other DApps and strategic partners. GXChain launched decentralized data marketplace as well which is serving hundreds of Chinese enterprises. GXChain team independently developed its main net and launched it in June 2017. Based on decentralization, cryptography, and smart token design, GXChain provides a leading solution for the data economy by developing multiple trusted data modules. Data uploading, storage, computation, and exchange has been gradually realized with many commercialized applications.
    </base-section-heading>
  </base-section>
</template>

<script>
  export default {
    name: 'SectionThemeFeatures',

    data: () => ({
      features: [
        {
          title: 'Pixel Perfect Design',
          icon: 'mdi-fountain-pen-tip',
        },
        {
          title: 'Retina Ready',
          icon: 'mdi-cellphone',
        },
        {
          color: 'primary',
          dark: true,
          title: 'Easily Customizable',
          icon: 'mdi-pencil-box-outline',
        },
        {
          title: 'Image Parallax',
          icon: 'mdi-image-size-select-actual',
        },
        {
          title: 'Seo Optimized',
          icon: 'mdi-ice-pop',
        },
        {
          title: '24/7 Support',
          icon: 'mdi-help-circle-outline',
        },
      ],
    }),
  }
</script>
