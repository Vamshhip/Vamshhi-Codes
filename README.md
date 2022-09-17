<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>My Favorite Things</title>
</head>
<body>

	<header>	
		<h1>My Favorite Things</h1>
		<!-- Primary Navigation -->
		<nav>
			<ul>
				<li>
					<a href="index.html">Home</a>
				</li>
				<li>
					<a href="animals.html">Animals</a>
				</li>
				<li>
					<a href="movies.html">Movies</a>
				</li>
			</ul>
		</nav>

		<!-- Secondary Navigation -->
		<nav>
			<ul>
				<li>
					<a href="#cakeRecipe">Chocolate Cake Recipe</a>
				</li>
				<li>
					<a href="#ramenRecipe">Ramen Recipe</a>
				</li>
			</ul>
		</nav>
		
	</header>

	<main>	
		<h2>Favorite Food</h2>

		<article>
			<h3>Chocolate Cake</h3>

			<section id="cakeRecipe">
				<h4>Recipe</h4>
				<p>Lorem <a href="https://www.youtube.com">ipsum dolor</a> sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br><br><br>Ut enim ad minim veniam, quis <a href="https://www.wikipedia.org">Visit Wikipedia</a> nostrud exercitation ullamco.</p>

				<!-- bold & italics -->
				<p>
					My <em>favorite</em> food is <b>chocolate cake.</b>
					<br> 
					<strong>Warning: Cake contains nuts.</strong>
					<br> 
					<i>All the problems in the world are solved by chocolate -Anonymous.</i>
				</p>

			</section>

			<section>
				<h4>History</h4>
				<p>Lorem ipsum dolor sit <a href="https://www.worldwildlife.org">WWF Website</a> amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>

				<pre>
					I had a cat, 
					Who was so fat. 
					He could not even, 
					Sit on his mat. 
					He had a     hat, 
					That did not fit. 
					He put it on, 
					And then it split
				</pre>

				<p>
					I had a cat, 
					Who was so fat. 
					He could not even, 
					Sit on his mat. 
					He had a     hat, 
					That did not fit. 
					He put it on, 
					And then it split
				</p>

				<!-- wbr -->
				<p>Thisisa<wbr>veryvery<wbr>veryvery<wbr>veryveryvery<wbr>veryveryvery<wbr>veryvery<wbr>veryveryvery<wbr>veryvery<wbr>veryver<wbr>yveryvery<wbr>veryveryvery<wbr>veryvery<wbr>longword</p>

				<aside>
					<h5>Trivia</h5>
					<p>Chocolate is made from <mark>cocoa</mark> beans</p>
				</aside>

				<!-- del & ins -->
				<p>I like <del>vanilla</del> <ins>chocolate</ins> cake</p>

				<!-- sup & sub -->
				<p>2<sup>2</sup> = 4</p>
				<p>Chemical formula of water is H<sub>2</sub>O</p>

			</section>
		</article>

		<hr>

		<article>
			<h3>Ramen</h3>

			<section id="ramenRecipe">
				<h4>Recipe</h4>
				<h5>Ingredients</h5>
				<!-- unordered lists -->
				<ul>
				  	<li>Broth
				  		<ul>
				  			<li>Broth
				  				<ul>
						  			<li>Broth</li>
								  	<li>Noodles</li>
									<li>Vegetables</li>
									<li>Seasoning</li>
						  		</ul>
				  			</li>
						  	<li>Noodles</li>
							<li>Vegetables</li>
							<li>Seasoning</li>
				  		</ul>
				  	</li>
				  	<li>Noodles</li>
					<li>Vegetables</li>
					<li>Seasoning</li>
			   	</ul>

			   	<h5>Instructions</h5>
			   	<!-- ordered lists -->
			   	<ol start="10" reversed>
			   		<li>Boil vegetables in broth.</li>
				   	<li>Add noodles & cook for 5 min.</li>
				   	<li>Season with spice mix.</li>
			   	</ol>

			   	<ol reversed>
			   		<li>Boil vegetables in broth.</li>
				   	<li>Add noodles & cook for 5 min.</li>
				   	<li>Season with spice mix.</li>
			   	</ol>

			</section>

			<section>
				<h4>History</h4>
				<!-- description list -->
				<dl>
					<dt>Ramen</dt>
					<dd>- Japanese noodle soup</dd>
				</dl>
			</section>
		</article>
	</main>

	<footer>
		<!-- mailto: -->
		<a href="mailto:coderange@example.com">Email Code Range</a>
		<br>
		<!-- tel: -->
		<a href="tel:123 456 7890">Call Us</a>
		<br>
		<a href="terms.html">Terms of use</a>
		<br>
		<a href="policy.html">Privacy policy</a>

		<!-- small -->
		<p><small>Copyright 2020 Code Range, Juthika Shetye</small></p>
	</footer>
</body>
</html>
