<!DOCTYPE html>
<html lang="en-PH">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Francis Coffee Shop</title>
<style>
  body { 
    font-family: 'Poppins', sans-serif; 
    background: linear-gradient(to bottom, #f7efe5, #e7d6c4); 
    margin:0; padding:0; text-align:center;
  }

  header { 
    background:#4e342e; color:white; padding:30px; 
    font-size:2rem; font-weight:700;
    box-shadow:0 4px 8px rgba(0,0,0,0.2);
  }

  #loginForm { margin:30px auto; width:300px; }
  input { width:90%; padding:10px; margin:8px 0; border-radius:5px; border:1px solid #ccc; }
  button { 
    margin:5px 2px; padding:10px 20px; cursor:pointer; 
    background:#4e342e; color:white; border:none; border-radius:5px;
    transition: 0.3s;
  }
  button:hover { background:#6d4c41; }

  #cart { 
    margin:20px 0; font-weight:bold; padding:10px; background:#fff8e1; 
    border-radius:8px; display:inline-block; box-shadow:0 3px 6px rgba(0,0,0,0.2);
  }

  #clearCartBtn { margin-bottom:20px; }

  .products { 
    display:flex; flex-wrap:wrap; justify-content:center; gap:25px; display:none; 
  }

  .product { 
    background:white; border-radius:15px; padding:15px; width:200px; 
    box-shadow:0 6px 12px rgba(0,0,0,0.15); transition:0.3s; 
  }

  .product:hover { 
    transform:translateY(-5px); 
    box-shadow:0 8px 16px rgba(0,0,0,0.25); 
  }

  .product img { width:100%; height:150px; object-fit:cover; border-radius:10px; }
  .product p { margin:10px 0; font-weight:600; }

  textarea { 
    margin-top:20px; width:90%; max-width:400px; height:80px; border-radius:8px; 
    padding:8px; border:1px solid #ccc; resize:none; display:none; 
  }

  footer { background:#4e342e; color:white; padding:15px; margin-top:30px; }
</style>
</head>
<body>

<header>☕ Francis Coffee Shop ☕</header>

<!-- LOGIN -->
<div id="loginForm">
  <input type="text" id="username" placeholder="Username">
  <input type="password" id="password" placeholder="Password">
  <button onclick="login()">Login</button>
</div>

<!-- CART -->
<div id="cart" style="display:none;">🛒 Items in Cart: <span id="itemCount">0</span> | Total: ₱<span id="totalPrice">0</span></div>
<button onclick="clearCart()" id="clearCartBtn" style="display:none;">🧹 Clear Cart</button>
<button onclick="logout()" id="logoutBtn" style="display:none;">🚪 Logout</button>

<!-- PRODUCTS -->
<div class="products" id="productList">
  <div class="product">
    <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=800&q=80" alt="Mocha Latte">
    <p>Mocha Latte - ₱150</p>
    <button onclick="addToCart('Mocha Latte',150)">Add to Cart</button>
    <button onclick="buyNow('Mocha Latte',150)">Buy Now</button>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=800&q=80" alt="Cappuccino">
    <p>Cappuccino - ₱140</p>
    <button onclick="addToCart('Cappuccino',140)">Add to Cart</button>
    <button onclick="buyNow('Cappuccino',140)">Buy Now</button>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1521305916504-4a1121188589?auto=format&fit=crop&w=800&q=80" alt="Caramel Macchiato">
    <p>Caramel Macchiato - ₱160</p>
    <button onclick="addToCart('Caramel Macchiato',160)">Add to Cart</button>
    <button onclick="buyNow('Caramel Macchiato',160)">Buy Now</button>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1510626176961-4b7f1e222ee6?auto=format&fit=crop&w=800&q=80" alt="Iced Americano">
    <p>Iced Americano - ₱120</p>
    <button onclick="addToCart('Iced Americano',120)">Add to Cart</button>
    <button onclick="buyNow('Iced Americano',120)">Buy Now</button>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1514432324607-a09d9f84d0c6?auto=format&fit=crop&w=800&q=80" alt="Flat White">
    <p>Flat White - ₱130</p>
    <button onclick="addToCart('Flat White',130)">Add to Cart</button>
    <button onclick="buyNow('Flat White',130)">Buy Now</button>
  </div>
</div>

<textarea id="feedback" placeholder="Drop your feedback here about my coffee shop..."></textarea>

<script>
let itemCount = 0;
let totalPrice = 0;
let loggedIn = false;

// LOGIN FUNCTION
function login(){
  const user = document.getElementById('username').value;
  const pass = document.getElementById('password').value;
  if(user === "admin" && pass === "123"){
    loggedIn = true;
    alert("Login successful! Welcome " + user);

    // hide login form
    document.getElementById('loginForm').style.display = "none";

    // show products, cart, feedback, logout button
    document.getElementById('productList').style.display = "flex";
    document.getElementById('cart').style.display = "inline-block";
    document.getElementById('clearCartBtn').style.display = "inline-block";
    document.getElementById('feedback').style.display = "block";
    document.getElementById('logoutBtn').style.display = "inline-block";
  } else {
    alert("Invalid username or password!");
  }
}

// LOGOUT FUNCTION
function logout(){
  loggedIn = false;
  itemCount = 0;
  totalPrice = 0;
  alert("Logged out successfully!");

  // reset UI
  document.getElementById('loginForm').style.display = "block";
  document.getElementById('productList').style.display = "none";
  document.getElementById('cart').style.display = "none";
  document.getElementById('clearCartBtn').style.display = "none";
  document.getElementById('logoutBtn').style.display = "none";
  document.getElementById('feedback').style.display = "none";
  document.getElementById('itemCount').innerText = 0;
  document.getElementById('totalPrice').innerText = 0;
}

// CART FUNCTIONS
function addToCart(name, price){
  if(!loggedIn){
    alert("Please login first!");
    return;
  }
  itemCount++;
  totalPrice += price;
  document.getElementById('itemCount').innerText = itemCount;
  document.getElementById('totalPrice').innerText = totalPrice;
  alert(name + " added to cart!");
}

function buyNow(name, price){
  if(!loggedIn){
    alert("Please login first!");
    return;
  }
  alert("You bought " + name + " for ₱" + price + "!");
}

function clearCart(){
  itemCount = 0;
  totalPrice = 0;
  document.getElementById('itemCount').innerText = itemCount;
  document.getElementById('totalPrice').innerText = totalPrice;
  alert("Cart cleared!");
}
</script>

<footer>© 2025 Francis Coffee Shop</footer>
</body>
</html>

<script>
// ... existing cart/login functions remain the same

function buyNow(name, price){
  if(!loggedIn){
    alert("Please login first!");
    return;
  }
  // Redirect to Shopee search page for the product
  const query = encodeURIComponent(name + " coffee");
  const shopeeURL = `https://shopee.ph/search?keyword=${query}`;
  window.open(shopeeURL, "_blank"); // opens in new tab
}
</script>
