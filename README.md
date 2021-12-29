# LGMVIP---WebDev

<!DOCTYPE html>
<html>
<head>
	<title>Photoweb</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body>
<header>
	<nav>
		<div class="logo">
			Photo<span>pi</span>X
		</div>
		<div class="menu">
			<a href="#">Home</a>
			<a href="#">About</a>
			<a href="#">Gallery</a>
			<a href="#">Contact</a>
		</div>
		<div class="icon">
			<i class="fa fa-search"></i>
			<a href="#">Login</a>

		</div>
	</nav>


	<section class="h-text">
		<i class="fa fa-camera" id="camera"></i>
		<h1 data-aos="zoom-in-down" data-aos-delay="100">Capturing the moments that captivate your heart.</h1>
		<input type="text" name="" placeholder="Search here...">
		<button><i class="fa fa-search"></i></button>

		
	</section>
</header>

<section class="filter-gallery">
	<div class="portfolio-menu">
			<ul>
				<li class="active" data-filter="*"> All</li>
				<li data-filter=".web"> Nature</li>
				<li data-filter=".seo">Faishon</li>
				<li data-filter=".graphics">Wedding</li>
			</ul>
		</div>
		<div class="portfolio-item">
			<div class="item web"  data-aos="flip-left" data-aos-offset="100" data-aos-delay="100">
				<img src="img/p1.jpg" width="100" height="100">
			</div>

			<div class="item seo"  data-aos="flip-left" data-aos-offset="100" data-aos-delay="200">
				<img src="img/p2.jpg" width="100" height="100">
			</div>
			<div class="item graphics"  data-aos="flip-left" data-aos-offset="100" data-aos-delay="300">
				<img src="img/p3.jpg" width="100" height="100">
			</div>
			<div class="item web" data-aos="zoom-in" data-aos-offset="100" data-aos-delay="100">
				<img src="img/p4.jpg" width="100" height="100">
			</div>

			<div class="item seo" data-aos="zoom-in" data-aos-offset="100" data-aos-delay="200">
				<img src="img/p5.jpg" width="100" height="100">
			</div>
			<div class="item seo" data-aos="zoom-in" data-aos-offset="100" data-aos-delay="300">
				<img src="img/p6.jpg" width="100" height="100">
			</div>
			<div class="item graphics" data-aos="zoom-in-up" data-aos-offset="100" data-aos-delay="100">
				<img src="img/p7.jpg" width="100" height="100">
			</div>
			<div class="item graphics" data-aos="zoom-in-up" data-aos-offset="100" data-aos-delay="200">
				<img src="img/p8.jpg" width="100" height="100">
			</div>
			<div class="item graphics" data-aos="zoom-in-up" data-aos-offset="100" data-aos-delay="300">
				<img src="img/p9.jpg" width="100" height="100">
			</div>
		</div>
	
</section>


<!--- filter gallery end---->

<!-- slider start--->

<section class="members">
		<div class="member-info"  data-aos="zoom-in-up" data-aos-offset="100" data-aos-delay="100">
			<h1>Our <span>Informations</span></h1>
	<p>What our member says</p>
</div>


<div class="member-card"  data-aos="zoom-in-down" data-aos-offset="100" data-aos-delay="300">
	

	<img src="img/member.png">
	<p>
 			From Rajasthan,doing gym is good for healthy life. it helps our body to fit. it release stress from our mind.From Rajasthan,doing gym is good for healthy life. it helps our body to fit. it release stress from our mind.
	</p>
	<h2>* Maria Sharapova</h2>

	<img src="img/icon1.png" width="100">
	<img src="img/icon2.png" width="100">
	<img src="img/icon3.png" width="100">
	<img src="img/icon4.png" width="100">
</div>
<div class="m-images"  data-aos="zoom-in" data-aos-offset="100" data-aos-delay="300">
	<img src="img/s1.jpg">
	<img src="img/s2.jpg">
	<img src="img/s3.jpg">
	<img src="img/s4.jpg">
	<img src="img/s5.jpg">
	<img src="img/s6.jpg">
	

</div>
</section>





<footer>
	<div class="newsletter">
		<div data-aos="fade-up" data-aos-offset="200">
			<h2>Subscribe our newsletter</h2>
			<p>We’re a team of non-cynics who truly care for our work.</p>
		</div>
		<div class="n-text" data-aos="fade-up-right" data-aos-offset="200">
			<label>
				<input type="text" name="" placeholder="Enter your email">
				<button>Subscribe</button>

			</label>
		</div>
	</div>	


	<div class="f-contact" data-aos="zoom-in-up" data-aos-offset="200">
		<div>
			<h1>Information</h1>
			<p>Lorem ipsum dolor sit amet, consectetur elit. Nihil sit dicta.</p>
			
			<i class="fa fa-whatsapp"></i>
			<i class="fa fa-instagram"></i>
			<i class="fa fa-telegram"></i>
			<i class="fa fa-twitter"></i>
		</div>


		<div>
			<h1>Useful links</h1>
			<p>About us</p>
			<p>Gallery</p>
			<p>Blog posts</p>
			<p>Pricing plans</p>

		</div>

		<div>
			<h1>Details</h1>
			<p>Photographers</p>
			<p>Gallery</p>
			<p>About</p>
			<p>Pricing plans</p>

		</div>

		<div>
			<h1>Help & Support</h1>
			<p>Privacy policy</p>
			<p>Term & conditions</p>
			<p>Technical support</p>
			<p>Customer care</p>

		</div>
	</div>
</footer>













<script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>

<script src="https://unpkg.com/isotope-layout@3/dist/isotope.pkgd.min.js"></script>
<script>
	$('.portfolio-item').isotope({
  // options
  itemSelector: '.item',
  lnmmmayoutMode: 'fitRows'
});
		$('.portfolio-menu ul li').click(function(){
		$('.portfolio-menu ul li').removeClass('active');
		$(this).addClass('active');

			var selector = $(this).attr('data-filter');
		$('.portfolio-item').isotope({
			filter:selector
		});
		return false;
	});
</script>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init();

</script>
</body>
</html>


