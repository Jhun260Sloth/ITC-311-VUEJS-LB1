<style>

@import '@/assets/css/magnific-popup.min.css';

@import '@/assets/css/tooplate-style.css';

</style>


<template>



  
  </template>
  
  <script>
  
  // Import all images from the 'images' directory
  const imageContext = require.context('@/assets/images', false, /\.(png|jpg|jpeg|gif|svg)$/);

  // Create an object to store the imported images
  const images = {};

  imageContext.keys().forEach(key => {
    images[key.replace('./', '')] = imageContext(key);
  });

    export default {
      data() {
        return {
          images,
        };
      },
      mounted() {
        this.loadScripts();
      },
      methods: {
        loadScripts() {
          const scriptUrls = [
            '/js/imagesloaded.pkgd.min.js',
            '/js/isotope.pkgd.min.js',
            '/js/jquery.magnific-popup.min.js',
            '/js/jquery.min.js',

          ];
          const head = document.getElementsByTagName('head')[0];
          scriptUrls.forEach((scriptUrl) => {
            const script = document.createElement('script');
            script.src = scriptUrl;
            script.async = true;
            head.appendChild(script);
          });
        },
      },
    };
    
  </script>
  