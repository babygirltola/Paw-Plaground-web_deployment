# Paw-Plaground-web_deployment
Paw playground is an adoption center
<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>CodePen - A Pen by babygirltola</title>
  <link rel='stylesheet' href='https://codepen.io/babygirltola/pen/RwxwZMY.css'><link rel="stylesheet" href="./style.css">

</head>
<body>
<!-- partial:index.partial.html -->
<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>My Landing Page</title>
	<link href="https://fonts.googleapis.com/css2?family=Lato:wght@300&display=swap" rel="stylesheet"> 
	<script src="https://kit.fontawesome.com/be4b8167f4.js" crossorigin="anonymous"></script>
	<link rel="stylesheet" href="style.css">
</head>
<body>
		<nav>
			<div class="logo">
				<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQq695C-33XZ-z6VPzeGa4TL29tDYLVOxjY5BJ_udDMMEYBSc7IKSzY2Vot&s=10"alt="user">
			</div>
			 <div>  <label for="AVATAR">Take a photo</label></div>
		<input  id="AVATAR" name="avatar" type="file">
			
		</label><br><br>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">About</a></li>
				<li><a href="#">Menu</a></li>
				<li><a href="#">Contact</a></li>

			</ul>
		</nav>
	<header>
		<button id="toggle" class="toggle">
			<i class="fas fa-bars fa-2x"></i>
</button>
		<p>	<h1>PAW PLAYGROUND</h1>
<p>Paw Playground is an Adoption Center for pets(dogs and cats). Paw playground was opened in November 2020. 
 Since that opening, the division has been dedicated toward improving the lives of animals in our community</p>
	<button class="cta-btn" id="open">Sign Up</button>
	</header>
	<main class="container">
<p>We are dedicated to improving lives of animals by:</p>
<!— Disc Bullets—>
<ul>
<li>Sheltering and adopting animals into loving, forever homes.
Working with prospective owners to enhance animal welfare.</li>
<li>Reuniting lost pets with their owners.</li>
</ul>
<b>
<h2> DO YOU WANT TO ADOPT A PET?</h2>
</b>
		<button class="cta-btn" 
	<main class="container">
	</main>
		<div class="modal-container" id="modal">
			<div class="modal">
				<button class="close-btn" id="close"><i class="fa fa-times"></i></button>
				<div class="modal-header">
					<h3>Sign Up</h3>
				</div>
				<div class="modal-content">
				<p>Register here.</p>
					<form class="modal-form">
						<div>
							<label for="name">Name</label>
							<input type="text" id="name" placeholder="Enter Name" class="form-input">
						</div>
						<div>
							<label for="email">Email</label>
							<input type="email" id="email" placeholder="Enter Email" class="form-input">
						</div>
						<div>
							<label for="password">Password</label>
							<input type="password" id="password" placeholder="Enter Password" class="form-input">
						</div>
						<div>
							<label for="password2">Confirm Password</label>
							<input type="password" id="password2" placeholder="Confirm Password" class="form-input">
						</div>
						<input type="submit" value="submit" class="submit-btn">
					</form>
				</div>
			</div>
		</div>
	<script>
		const modal = document.querySelector('#modal');
		const toggle = document.querySelector('#toggle');
		const close = document.querySelector('#close');
		const open = document.querySelector('#open');
		
		
		toggle.addEventListener('click', () => {
			document.body.classList.toggle('show-nav');
		});
		
		open.addEventListener('click', () =>{
			modal.classList.add('show-modal');
		});
		
		close.addEventListener('click', () =>{
			modal.classList.remove('show-modal');
		});
		
		window.addEventListener('click', e => e.target == modal ? modal.classList.remove('show-modal') : false);

	</script>
	<p>HERE ARE A FEW PETS READY TO BE ADOPTED</p>
<!-- Disc Bullets-->
<ul>
<b>
<li> Meet Amy</li>
<p>Amy is 2 months old cat.
She loves giving cuddles and also receiving them.She loves everyone.
</p>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSbk1WWeFsgLcTjy7fZ4ox1AufC0_-NVmQhLw&usqp=CAU" alt="amy">
<li>Meet Tyler</li>
<p>Tyler is a home trained dog.
 He is 4 months old.
 Tyler is a huge fan of kids & he gets a little but playful sometimes.</p>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSC3e2OxbR1TBz8CyubdouI0Sw3sWWHqvYDJQ&usqp=CAU" alt="tyler">
<li>Meet Kylie</li>
<p>Kylie is a year old.
Most times she likes been in her own space but she's a very welcoming.</p>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBmnepkyx0FcG76JF4FniOe9r95Zk6_pX8YA&usqp=CAU" alt="Kylie">
<li>Meet Furry</li>
<p>Furry is a a year and a half old.
He's the oldest cat are our centre. He likes his space. He doesn't really like playful dogs like Tyler.</p>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdteG3fckedRBN30DvWnTKtpG5lpQ3_fi7SQ&usqp=CAU" alt="Furry">
<li>Meet Gray & Tan</li>
<p>Gray are Tan are a Twin,they do almost everything together. They are both one year old. They like making both human and pet friends.</p>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRTzh1EnHmKtHoXhWMKGYZJ9l3fv4-yN-i2qw&usqp=CAU" alt="Grey & Tan"
</b>
</ul>
<p>Before adoption,kindly answer these questions;</p>
<label for "multiLineInput">
<ol>
<li><h3>Have you owned a pet before?</h3></li>
<textarea id ="multiLineInput"></textarea>
<label for "multiLineInput">
<li><h3>Why do you want to adopt a pet?</h3></li>
<textarea id ="multiLineInput"></textarea>
<li><h3>How old are you?</li></h3>
<textarea id ="multiLineInput"></textarea>
</ol>
</body>
	  <div class="column subscribe">
		  <h3>Subscribe to our Email.</h3>
		  <div>
			<input type="email" placeholder="Your email id here" />
			<button>Subscribe</button>
		  </div>
		  <div class="social">
			<i class="fa-brands fa-facebook-square"></i>
			<i class="fa-brands fa-instagram-square"></i>
			<i class="fa-brands fa-twitter-square"></i>
		  </div>
		</div>
	  </div>
	  <div class="row secondary">
		<div>
		  <p><i class="fa-solid fa-phone"></i></p>
		  <p>📞+234 9025622071</p>
		</div>
		<div>
		  <p><i class="fas fa-envelope"</i></p>
		  <p>📩mail@paw playground.com</p>
		</div>
		<div>
		  <p><i class="fas fa-map-marker-alt"></i></p>
		  <p>📍2022 Paw Street</p>
		</div>
		<p>Copyright &copy; 2022 Paw playground | All Rights Reserved</p>
	  </div>
	</footer>
</html>
<!-- partial -->
  <script src='https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js'></script>
</body>
</html>
