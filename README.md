# Ex02 Commercial Website
## Date:14.08.2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## INDEX.HTML
hello.html
!<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Food Store</title>
  <link rel="stylesheet" href="co.css">
  
</head>
<body>

  <nav>
    <div class="nav-container">
      <div class="logo">
        <a href="#" style="color:white; font-size: 1.5rem; font-weight: bold;">OrderYourFood</a>
      </div>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="books.html">Dish</a></li>
      </ul>
    </div>
  </nav>

  <section class="hero" id="home">
    <div>
      <h1>Welcome to FoodStore</h1>
      <p style="color:rgb(82, 7, 111);">🍽️ Welcome to [ABC FOOD SHOP] – Your New Favorite Food Spot in Town! 🍔🌮🍰
        We’re excited to serve you delicious, freshly-made meals with a smile. Whether you're craving : juicy burgers, homemade pastries, or healthy vegan bowls. we’ve got something to satisfy every craving.</p>
    </div>
  </section>


  

</body>
</html>

# books.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="co.css">
</head>
<body>
    <nav>
        <div class="nav-container">
          <div class="logo">
            <a href="#" style="color:white; font-size: 1.5rem; font-weight: bold;">OrderYourFood</a>
          </div>
          <ul>
            <li><a href="hello.html">Home</a></li>
            <li><a href="books.html">Dish</a></li>
          </ul>
        </div>
      </nav>


    <section class="book-section" id="books">
        <div class="book">
          <img src="65.jpg" alt="Book 1">
          <h3>Chicken 65</h3>
          <p>Whether you like it as a snack, side, or meal, our Chicken 65</p>
          <p class="price">$199.00</p>
        </div>
        <div class="book">
          <img src="lol.jpg" alt="Book 2">
          <h3>Chicken Lolipop</h3>
          <p>Crunchy on the outside, juicy on the inside, and packed with mouth-watering flavor!</p>
          <p class="price">$299.00</p>
        </div>
        <div class="book">
          <img src="tikka.jpg" alt="Book 3">
          <h3>Chicken Tikka</h3>
          <p>Introducing our Signature Chicken Tikka – a fiery favorite for true flavor lovers!</p>
          <p class="price">$159.00</p>
        </div>
      </section>
      <footer>
        <p>&copy; 2025 FoodStore. All Rights Reserved.</p>
        <p>Name: HARISH B| Reg No: 212223040061</p>
      </footer>
    
      
      
</body>
</html>

## CSS
css
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    /* Navbar */
    nav {
      background-color: #333;
      color: white;
      padding: 1rem;
    }

    .nav-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .nav-container ul {
      display: flex;
      list-style-type: none;
    }

    .nav-container ul li {
      margin: 0 15px;
    }

    .nav-container ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .nav-container ul li a:hover {
      text-decoration: underline;
    }

  
.hero {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: url('1.jpg') center/cover no-repeat;
  color: white;
  text-align: center;
}


    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.5rem;
    }

    .book-section {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 2rem;
      background-color: #f4f4f4;
    }

    .book {
      flex: 1 1 300px;
      margin: 1rem;
      padding: 1.5rem;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      text-align: center;
    }

    .book img {
      width: 200px; 
      height: 300px; 
      object-fit: cover;
      border-radius: 8px;
    }

    .book h3 {
      margin: 1rem 0;
      font-size: 1.5rem;
    }

    .book p {
      color: #555;
      margin-bottom: 1rem;
    }

    .book .price {
      font-size: 1.25rem;
      font-weight: bold;
      color: #333;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    footer p {
      font-size: 1rem;
    }

    @media (max-width: 768px) {
      .nav-container {
        flex-direction: column;
        align-items: flex-start;
      }

      .hero h1 {
        font-size: 2.5rem;
      }

      .book-section {
        flex-direction: column;
        align-items: center;
      }



## OUTPUT

<img width="1907" height="1079" alt="Screenshot 2025-08-17 212535" src="https://github.com/user-attachments/assets/185384e8-47ce-4717-9644-ca2e0b136752" />


<img width="1906" height="1079" alt="Screenshot 2025-08-17 212546" src="https://github.com/user-attachments/assets/c0fa572e-ffb4-4315-94ce-fe21801b54c5" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
