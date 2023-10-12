<style>

@import '@/assets/css/magnific-popup.min.css';

@import '@/assets/css/tooplate-style.css';

@import '@/assets/css/responsive.css';

</style>


<template>



  
  </template>
  


  <script>
  
  // Import all images from the 'images' directory
  const imageContext = require.context('@/assets/images', false, /\.(png|jpg|jpeg|gif|svg)$/);

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
		  	'/js/jquery.min.js',
            '/js/imagesloaded.pkgd.min.js',
            '/js/isotope.pkgd.min.js',
            '/js/jquery.magnific-popup.min.js',
			'/js/manage.js',

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
  