# Ex.07 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hot Chocolate Restaurant</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5e9e4;
    }
    header {
      background: #5a2d2d;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
    }
    .hero {
      background: #fff;
      margin: 20px;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }
    .menu {
      margin: 20px;
      padding: 20px;
      background: white;
      border-radius: 10px;
      text-align: center;
    }
    .menu-items {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .item {
      background: #f7f2f0;
      padding: 10px;
      border-radius: 8px;
      width: 250px;
      text-align: center;
    }
    .item img {
      width: 250px;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 8px;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #5a2d2d;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hot Chocolate House</h1>
    <nav>
      <a href="#menu">Menu</a>
      <a href="#about">About</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome!</h2>
    <p>Enjoy warm, creamy and delicious hot chocolate.</p>
  </section>

  <section id="menu" class="menu">
    <h2>Menu</h2>
    <div class="menu-items">
      <div class="item">
        <img src="https://images.unsplash.com/photo-1684347417177-98b34adb6773?w=500&auto=format&fit=crop&q=60" alt="Classic Hot Chocolate">
        <h3>Classic Hot Chocolate - ₹120</h3>
        <p>Rich and creamy cocoa drink.</p>
      </div>

      <div class="item">
        <img src="https://plus.unsplash.com/premium_photo-1667031519192-ba1ed681751d?w=500&auto=format&fit=crop&q=60" alt="Dark Chocolate">
        <h3>Dark Chocolate - ₹150</h3>
        <p>Stronger cocoa flavour with less sweetness.</p>
      </div>

      <div class="item">
        <img src="https://plus.unsplash.com/premium_photo-1676074205853-c05eacc79417?w=500&auto=format&fit=crop&q=60" alt="Caramel Chocolate">
        <h3>Caramel Chocolate - ₹160</h3>
        <p>Hot chocolate with caramel syrup.</p>
      </div>
    </div>
  </section>

  <section id="about" class="menu">
    <h2>About Us</h2>
    <p>We make fresh hot chocolate using quality cocoa and milk.</p>
  </section>

  <footer>
    <p>Hot Chocolate House © 2025</p>
  </footer>
</body>
</html>
```

## OUTPUT:


![alt text](<WhatsApp Image 2025-11-20 at 08.53.00_b5e32c24.jpg>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.