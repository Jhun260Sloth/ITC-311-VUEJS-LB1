<style>

@import '@/assets/css/magnific-popup.min.css';

@import '@/assets/css/tooplate-style.css';

@import '@/assets/css/responsive.css';

</style>


<template>

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Nano Folio - Simple HTML Template</title>

</head>

<body>
	<div class="tm-container-fluid">
		<section class="tm-site-header tm-flex-center tm-mb-50 tm-bgcolor-1 tm-border-rounded">
			<i class="fas fa-heart fa-3x"></i>
			<h1>Nano Folio</h1>
		</section>

		<section class="tm-about tm-mb-80 tm-p-50 tm-bgcolor-2 tm-border-rounded">
			<div class="tm-about-header tm-flex-center">
				<i class="fas fa-users fa-2x"></i>
				<h2>About Us</h2>
			</div>
			<div class="tm-about-text">
				<p class="tm-mb-40">Nano Folio is simple HTML template with a minimal very light-weight custom CSS file. Max content width is 940 pixels. You can easily change the width or any part in this template. Gallery comes with a pop-up image and simple categories.</p>
				<p class="tm-mb-0">Please support Tooplate website by telling your friends about it. That is going to be very helpful for us. Feel free to <a rel="nofollow" href="https://www.tooplate.com/contact" target="_blank">message us</a> via email or live chat if you have anything to say.</p>
			</div>
		</section>

		<div class="tm-gallery-section tm-mb-80">
			<ul class="filters-button-group tm-mb-40">
				<li><a href="#" data-filter=".city">City</a></li>
				<li><a href="#" data-filter=".nature">Nature</a></li>
				<li><a href="#" data-filter=".portraits">Portraits</a></li>
				<li><a href="#" class="active" data-filter="*">Show All</a></li>
			</ul>
			<div class="tm-gallery">				
				<div class="tm-gallery-item city portraits">

		            <a :href="images['img-01.jpg']">
		            	<img :src="images['img-01.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>

				<div class="tm-gallery-item portraits">
          <a :href="images['img-02.jpg']">
		            	<img :src="images['img-02.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>

				<div class="tm-gallery-item city">
          <a :href="images['img-03.jpg']">
		            	<img :src="images['img-03.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
		        <div class="tm-gallery-item nature">
              <a :href="images['img-04.jpg']">
		            	<img :src="images['img-04.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
				<div class="tm-gallery-item city">
          <a :href="images['img-05.jpg']">
		            	<img :src="images['img-05.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
				<div class="tm-gallery-item city">
          <a :href="images['img-06.jpg']">
		            	<img :src="images['img-06.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
		        <div class="tm-gallery-item nature portraits">
              <a :href="images['img-07.jpg']">
		            	<img :src="images['img-07.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
				<div class="tm-gallery-item nature">
          <a :href="images['img-08.jpg']">
		            	<img :src="images['img-08.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
				<div class="tm-gallery-item nature">
          <a :href="images['img-09.jpg']">
		            	<img :src="images['img-09.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
		        <div class="tm-gallery-item nature portraits">
              <a :href="images['img-10.jpg']">
		            	<img :src="images['img-10.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
				<div class="tm-gallery-item nature">
          <a :href="images['img-11.jpg']">
		            	<img :src="images['img-11.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
				<div class="tm-gallery-item portraits">
          <a :href="images['img-12.jpg']">
		            	<img :src="images['img-12.jpg']" alt="City Scape" class="img-fluid" />
		            </a>
		        </div>
			</div>			
		</div>

		<section class="tm-contact tm-mb-50 tm-bgcolor-3 tm-border-rounded">
			<div class="tm-contact-header tm-flex-center">
				<i class="fas fa-map-pin fa-3x"></i>
				<h2>Contact</h2>
			</div>
			<div class="tm-contact-info">
				<address class="tm-mb-30">
					120 Curabitur sed tortor ultrices,
					congue odio eget, posuere urna.
					Praesent at rhoncus 10680
				</address>
				<div class="tm-text-white tm-mb-40">Tel: <a href="tel:0100200340" class="tm-link-white">010-020-0340</a></div>
				<div class="tm-flex">
					<a href="https://facebook.com" class="tm-social-link"><i class="fab fa-facebook"></i></a>
					<a href="https://twitter.com" class="tm-social-link"><i class="fab fa-twitter"></i></a>
					<a href="https://instagram.com" class="tm-social-link"><i class="fab fa-instagram"></i></a>
				</div>
			</div>
			<div class="tm-contact-form-container">
				<form id="contact-form" action="" method="POST" class="tm-contact-form">
		          	<input type="text" name="name" placeholder="name" required="" />
		          	<input type="email" name="email" placeholder="email" required="" />
		          	<textarea rows="5" name="message" class="tm-mb-30" placeholder="message" required=""></textarea>		          	
		          	<button type="submit" class="tm-right tm-btn-submit">send</button>          	
		        </form>    
			</div>
		</section>

		<footer class="tm-footer">
			Copyright 2020 Nano Folio - Design: <a rel="sponsored" href="https://www.tooplate.com" class="tm-link-gray">Tooplate</a>
		</footer>
	</div>

</body>
</html>
  
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
  