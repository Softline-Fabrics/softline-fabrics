<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Softline Fabrics - Online Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff9f5;
      margin: 0;
      padding-bottom: 50px;      
    }
      body {
  background-image: url('softline.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}


    header {
      background: linear-gradient(to right, #ff6a00, #ee0979);
      color: blanchedalmond;
      text-align: left;
      padding: 60px 40px;
        width: 100%;
        font-size: 40px;
    }
      p6 {
          
          text-align: center;
          text-decoration-color: black;
          font-size: 50px;
          display: block;
          color: black;
          padding: 40px 20px;
          margin: auto;
      }
      p  {
          
          margin: 0;
      }
 footer {
  text-align: center;
  padding: 9px;
  background-color: chocolate;
  color: white;
  width: 100%;
  background-size: cover
      }
    h1 {
      margin: 0;
    }

    .filters {
      text-align: center;
      padding: 10px;
    }

    .filters input[type="text"] {
      width: 300px;
      padding: 10px;
      border-radius: 10px;
      border: 1px solid #ccc;
      font-size: 16px;
    }

    .category-buttons, .fabric-buttons {
      display: list-item;
      justify-content: center;
      gap: 10px;
      flex-wrap: wrap;
      margin: 15px 0;
    }

    button {
      padding: 10px 20px;
      background-color: #f39c12;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      font-size: 10px;
    }

    button.active {
      background-color: #27ae60;
    }
 

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 13px;
      padding: 0 20px;
    }

    .product {
      width: 200px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      text-align: center;
      padding: 10px;
    }

    .product img {
      width: 100%;
      border-radius: 5px;
      height: 240px;
      object-fit: cover;
    }

    .buy-btn {
      display: block;
      margin-top: 10px;
      padding: 8px 15px;
      background: #e74c3c;
      color: white;
      border-radius: 20px;
      text-decoration: none;
    }
       /* WhatsApp Floating Button */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      padding: 15px;
      text-align: center;
      font-size: 24px;
      z-index: 100;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }

    .whatsapp-float:hover {
      transform: scale(1.1);
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }
        
        <title>Feedback</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fffaf6;
      margin: 0;
      padding: 3px;
    }

    .feedback-section {
      max-width: 400px;
      margin: 50px auto;
      background: white;
      padding: 5px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .feedback-section h2 {
      text-align: center;
      color: #e67e22;
    }

    label {
      display: contents;
      margin-top: 15px;
      font-weight: bold;
    }

    input, textarea {
      width: 100%;
      padding: 5px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 3px;
      font-size: 16px;
    }

    button {
      margin-top: 20px;
      padding: 12px 20px;
      background-color: #e67e22;
      color: white;
      border: none;
      border-radius: 25px;
      font-size: 16px;
      cursor: pointer;
      width: 100%;
    }

    button:hover {
      background-color: #d35400;
    }
  </style>
</head>
<body>

<header>
    <h1><strong>Softline Fabrics</strong></h1>
    <p4>Premium Unstitched Fabrics for Every Occasion</p4>
    <hr>
</header>

<div class="filters">
  <input type="text" id="searchBox" placeholder="Search by product name..." onkeyup="updateProducts()">
</div>
    
    <section style="display: inline-flex; gap: 20px; justify-content: center; padding: 20px;">
  <div>
    <img src="male%20winter.jpg" alt="Cotton Fabric" style="width: 250px; border-radius: 10px;">
    <p>Winter Collection</p>
  </div>
  <div>
    <img src="mens%20summer.jpg" alt="Cotton Fabric" style="width: 250px; border-radius: 10px;">
    <p style="text-align: center;">Summer Collection</p>
  </div>
   <div>
    <img src="mens%20unstiched.webp" alt="Cotton Fabric" style="width: 250px; border-radius: 10px;">
    <p style="text-align: center;">Unstiched</p>
  </div>
     <div>
    <img src="winter%20womens%20clothing.webp" alt="Cotton Fabric" style="width: 250px; border-radius: 10px;">
    <p style="text-align: center;">Winter Collection</p>
  </div>
         <div>
    <img src="winter%20collection.webp" alt="Cotton Fabric" style="width: 250px; border-radius: 10px;">
    <p style="text-align: center;">Winter Collection</p>
  </div>
         <div>
    <img src="summer%20collection.jpg" alt="Cotton Fabric" style="width: 250px; border-radius: 10px;">
    <p style="text-align: center;">Summer Collection</p>
  </div>
         <div>
    <img src="summer%20unstiched.webp" alt="Cotton Fabric" style="width: 250px; border-radius: 10px;">
    <p style="text-align: center;">Summer Collection</p>
  </div>
</section>

<p6><strong>Our Products</strong></p6>
<hr>
<div class="category-buttons">
  <button onclick="filterCategory('All')" class="active">All</button>
  <button onclick="filterCategory('Men')">Men</button>
  <button onclick="filterCategory('Women')">Women</button>
  <button onclick="filterCategory('Kids')">Kids</button>
</div>

<div class="fabric-buttons">
  <button onclick="filterFabric('All')" class="active">All Fabrics</button>
  <button onclick="filterFabric('Summer Collection')">Summer Collection</button>
  <button onclick="filterFabric('Winter Collection')">Winter Collection</button>
  <button onclick="filterFabric('Discounted')">Discounted</button>
</div>
         
    <div class="products" id="product-list">
    <div class="product" data-category="Men" data-fabric="Summer Collection" data-name="Men Cotton Suit">
    <img src="cotton.jpg" alt="Men Cotton">
    <h3>Men Cotton Suit</h3>
    <p>Rs3500</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Men Cotton" target="_blank">Buy Now</a>
   </div>
             
             
    <div class="product" data-category="Men" data-fabric="Discounted" data-name="Men Cotton Suit">
    <img src="cotton.jpg" alt="Men Cotton">
    <h3>Men Cotton Suit</h3>
    <p><del>Rs3500</del>
    </p><p>Rs3000</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Men Cotton" target="_blank">Buy Now</a>
   </div>

                 
    <div class="product" data-category="Men" data-fabric="Summer Collection" data-name="Men Cotton Suit">
    <img src="cotton.jpg" alt="Men Cotton">
    <h3>Men Cotton Suit</h3>
    <p>Rs2500</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Men Cotton" target="_blank">Buy Now</a>
   </div>

    
    <div class="product" data-category="Men" data-fabric="Discounted" data-name="Men Cotton Suit">
    <img src="cotton.jpg" alt="Men Cotton">
    <h3>Men Cotton Suit</h3>
    <p><del>Rs4500</del></p>
    <p>Rs3500</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Men Cotton" target="_blank">Buy Now</a>
  </div>


  <div class="product" data-category="Women" data-fabric="Winter Collection" data-name="Women Winter Collection">
    <img src="women%20silk.webp" alt="Women Silk">
    <h3>Women Silk Dress</h3>
    <p>Rs4999</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Women Silk" target="_blank">Buy Now</a>
  </div>
                         <div class="product" data-category="Women" data-fabric="Winter Collection" data-name="Women Winter Collection">
    <img src="women%20silk.webp" alt="Women Silk">
    <h3>Women Silk Dress</h3>
    <p>Rs5999</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Women Silk" target="_blank">Buy Now</a>
  </div>
                         
                         <div class="product" data-category="Women" data-fabric="Winter Collection" data-name="Women Winter Collection">
    <img src="women%20silk.webp" alt="Women Silk">
    <h3>Women Silk Dress</h3>
    <p>Rs8999</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Women Silk" target="_blank">Buy Now</a>
  </div>

    <div class="product" data-category="Women" data-fabric="Summer Collection" data-name="Women Summer Collection">
    <img src="women%20cotton.jpg" alt="Women Cotton">
    <h3>Women Cotton Suit</h3>
    <p>Rs7999</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Women Cotton" target="_blank">Buy Now</a>
  </div>
    
                           <div class="product" data-category="Women" data-fabric="Summer Collection" data-name="Women Summer Collection">
    <img src="women%20cotton.jpg" alt="Women Cotton">
    <h3>Women Cotton Suit</h3>
    <p>Rs8999</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Women Cotton" target="_blank">Buy Now</a>
  </div>
    
    
                           <div class="product" data-category="Women" data-fabric="Summer Collection" data-name="Women Summer Collection">
    <img src="women%20cotton.jpg" alt="Women Cotton">
    <h3>Women Cotton Suit</h3>
    <p>Rs8999</p>
    <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Women Cotton" target="_blank">Buy Now</a>
  </div>
    
  <div class="product" data-category="Kids" data-fabric="Discounted" data-name="Discounted">
    <img src="wash&wear.jpg" alt="Kids Linen">
    <h3>Kids Linen Set</h3>
    <p><del>Rs2999</del></p>
      <p>Rs2599</p>
   <a class="buy-btn" href="https://wa.me/923319188629text=Hi, I'm interested in the Kids Linen" target="_blank">Buy Now</a>
  </div>
  
</div>

<script>
  let selectedCategory = 'All';
  let selectedFabric = 'All';

  function filterCategory(category) {
    selectedCategory = category;
    document.querySelectorAll(".category-buttons button").forEach(btn => btn.classList.remove("active"));
    event.target.classList.add("active");
    updateProducts();
  }

  function filterFabric(fabric) {
    selectedFabric = fabric;
    document.querySelectorAll(".fabric-buttons button").forEach(btn => btn.classList.remove("active"));
    event.target.classList.add("active");
    updateProducts();
  }

  function updateProducts() {
    const searchQuery = document.getElementById("searchBox").value.toLowerCase();
    const products = document.querySelectorAll('.product');

    products.forEach(product => {
      const matchesCategory = (selectedCategory === 'All' || product.dataset.category === selectedCategory);
      const matchesFabric = (selectedFabric === 'All' || product.dataset.fabric === selectedFabric);
      const matchesSearch = product.dataset.name.toLowerCase().includes(searchQuery);

      if (matchesCategory && matchesFabric && matchesSearch) {
        product.style.display = 'block';
      } else {
        product.style.display = 'none';
      }
    });
  }
</script>
    
    
    <hr>
    
    <section id="about" style="background-color: #fffaf5; padding: 60px 20px; font-family: Arial, sans-serif;">
  <div style="max-width: 900px; margin: auto; text-align: center;">
    <h2 style="font-size: 36px; color: #e67e22; margin-bottom: 20px;">About Us</h2>
    <p style="font-size: 18px; color: #444; line-height: 1.8;">
      At <strong>Softline Fabrics</strong>, we believe that fashion begins with the fabric.  
      We bring you a handpicked collection of premium unstitched materials that reflect tradition, style, and quality.
    </p>
    <p style="font-size: 18px; color: #444; line-height: 1.8;">
      Whether you’re looking for soft cottons, luxurious silks, or elegant linens, our fabrics are chosen to inspire your creativity.  
      Our goal is simple — to help you look your best, in styles tailored by you, for you.
    </p>
    <p style="font-size: 18px; color: #444; line-height: 1.8;">
      We’re passionate about quality, affordability, and giving our customers the freedom to express their style.  
      Join our growing community of fabric lovers and experience unstitched fashion like never before.
    </p>
    <p style="margin-top: 30px; font-size: 16px; color: #999;">
      💬 Have a question? <a href="https://wa.me/923319188629" style="color: #e67e22; text-decoration: none;">Chat with us on WhatsApp!</a>
    </p>
  </div>
</section>

    <hr>
     <!-- WhatsApp Floating Button -->
  <a href="https://wa.me/=923319188629text=Hi, I'm interested in your unstitched fabrics!" class="whatsapp-float" target="_blank" title="Chat on WhatsApp">💬</a>
 </body>
    <footer>
    <p2>📞 +92-3319188629 | ✉️softlineunstiched@gmail.com</p2>
    <p3>📸 Follow us on Instagram: <strong>@Softline.Unstichedfabrics</strong></p3>
  </footer>
<div class="feedback-section">
  <h2><strong>Share Your Feedback</strong></h2>
    <hr>
  <form onsubmit="submitFeedback(event)">
    <label for="name">Your Name:</label>
    <input type="text" id="name" required>

    <label for="email">Your Email:</label>
    <input type="email" id="email" required>

    <label for="message">Your Message:</label>
    <textarea id="message" rows="3" required></textarea>

    <button type="submit">Send Feedback</button>
  </form>
</div>

<script>
  function submitFeedback(event) {
    event.preventDefault();
    
    // You can connect this to a backend later
    const name = document.getElementById('name').value;
    alert(`Thank you for your feedback, ${name}!`);

    // Clear the form
    document.querySelector('form').reset();
  }
</script>
    <script>
  function submitFeedback(event) {
    event.preventDefault();
    
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;

    const whatsappMessage = `Feedback from ${name}%0AEmail: ${email}%0AMessage: ${message}`;
    
    window.open(`https://wa.me/923319188629text=${whatsappMessage}`, '_blank');

    document.querySelector('form').reset();
  }
</script>

 

</html>


