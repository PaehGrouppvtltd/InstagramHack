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
function likePost(element) {
  if (element.src.includes('like.png')) {
    element.src = 'https://img.icons8.com/fluency-systems-filled/24/fa314a/like.png';
  } else {
    element.src = 'https://img.icons8.com/material-outlined/24/000000/like.png';
  }
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Instagram Clone</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>
<body>
  <nav class="navbar">
    <div class="nav-wrapper">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" class="brand-img" alt="Instagram Logo">
      <input type="text" class="search-box" placeholder="Search">
      <div class="nav-items">
        <img src="https://img.icons8.com/material-outlined/24/000000/home.png">
        <img src="https://img.icons8.com/material-outlined/24/000000/filled-like.png">
        <img src="https://img.icons8.com/material-outlined/24/000000/add.png">
        <img src="https://img.icons8.com/material-outlined/24/000000/compass.png">
        <img src="https://img.icons8.com/material-outlined/24/000000/user.png">
      </div>
    </div>
  </nav>

  <main class="main-container">
    <section class="feed">
      <div class="post">
        <div class="post-header">
          <img src="https://randomuser.me/api/portraits/women/44.jpg" class="user-img">
          <span class="username">jane_doe</span>
        </div>
        <img src="https://source.unsplash.com/random/600x400?nature" class="post-img">
        <div class="post-actions">
          <img src="https://img.icons8.com/material-outlined/24/000000/like.png" onclick="likePost(this)">
          <img src="https://img.icons8.com/material-outlined/24/000000/speech-bubble.png">
          <img src="https://img.icons8.com/material-outlined/24/000000/paper-plane.png">
        </div>
        <p class="caption"><b>jane_doe</b> Loving this view 🌄</p>
      </div>
    </section>

    <aside class="sidebar">
      <div class="profile">
        <img src="https://randomuser.me/api/portraits/men/32.jpg" class="user-img">
        <div>
          <p class="username">john_smith</p>
          <p class="subtext">John Smith</p>
        </div>
      </div>

      <div class="suggestions">
        <p>Suggestions For You</p>
        <div class="suggestion">
          <img src="https://randomuser.me/api/portraits/women/65.jpg" class="user-img">
          <div>
            <p class="username">emma_w</p>
            <p class="subtext">New to Instagram</p>
          </div>
          <button class="follow-btn">Follow</button>
        </div>
      </div>
    </aside>
  </main>
</body>
</html>
