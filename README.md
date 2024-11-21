<!DOCTYPE html>
<html>
<head>
	<title>Access Our Tool</title>
	<style>
		body {
			font-family: Arial, sans-serif;
		}
		.container {
			width: 80%;
			margin: 40px auto;
			background-color: #f9f9f9;
			padding: 20px;
			border: 1px solid #ddd;
			border-radius: 10px;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}
		.step {
			margin-bottom: 20px;
		}
		.button {
			background-color: #4CAF50;
			color: #fff;
			padding: 10px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
		}
		.button:hover {
			background-color: #3e8e41;
		}
	</style>
</head>
<body>
	<div class="container">
		<h2>Access Our Tool</h2>
		<p>Follow these steps to access our tool:</p>
		
		<!-- Step 1: Payment -->
		<div class="step">
			<h3>Step 1: Make Payment</h3>
			<p>Pay using one of the following methods:</p>
			<ul>
				<li>Credit/Debit Card</li>
				<li>Net Banking</li>
				<li>UPI</li>
			</ul>
			<button class="button">Proceed to Payment</button>
		</div>
		
		<!-- Step 2: Payment Confirmation -->
		<div class="step">
			<h3>Step 2: Payment Confirmation</h3>
			<p>Once payment is successful, you will receive a confirmation email.</p>
		</div>
		
		<!-- Step 3: Access Tool -->
		<div class="step">
			<h3>Step 3: Access Tool</h3>
			<p>Click on the link provided in the email to access our tool.</p>
		</div>
		
		<!-- Payment Gateway Integration -->
		<form action="payment_gateway_url" method="post">
			<input type="hidden" name="amount" value="price">
			<input type="hidden" name="product_id" value="product_id">
			<input type="hidden" name="callback_url" value="callback_url">
			<button class="button">Pay Now</button>
		</form>
	</div>
</body>
</html>
