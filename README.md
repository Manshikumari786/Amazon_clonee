# Amazon_clonee
Amazon Clone using HTML and CSS

<!DOCTYPE html>
<html>
<head>
	<title>Simple Amazon Clone</title>
	<style>
		/* Your CSS styles here */

		body {
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}

		.product {
			border: 1px solid #ccc;
			border-radius: 5px;
			padding: 10px;
			margin: 10px;
			text-align: center;
			background-color: #f9f9f9;
		}

		.product img {
			max-width: 100%;
			height: auto;
		}

		.product h3 {
			margin: 10px 0;
		}

		.product a {
			text-decoration: none;
			color: #000;
			font-weight: bold;
		}
	</style>
</head>
<body>
	<div class="product">
		<img src="product1.jpg" alt="Product 1">
		<h3><a href="https://www.google.com">Product 1</a></h3>
		<p>Product description goes here.</p>
		<p>$99.99</p>
	</div>
	<div class="product">
		<img src="product2.jpg" alt="Product 2">
		<h3><a href="https://www.google.com">Product 2</a></h3>
		<p>Product description goes here.</p>
		<p>$149.99</p>
	</div>
    <div class="product">
		<img src="product1.jpg" alt="Product 1">
		<h3><a href="https://www.google.com">Product 1</a></h3>
		<p>Product description goes here.</p>
		<p>$99.99</p>
	</div>
	<div class="product">
		<img src="product2.jpg" alt="Product 2">
		<h3><a href="https://www.google.com">Product 2</a></h3>
		<p>Product description goes here.</p>
		<p>$149.99</p>
	</div>
	<!-- Repeat the above product structure for the other products -->

	<footer>
		<p>&copy; 2023 Simple Amazon Clone</p>
	</footer>
</body>
</html>
