# Ex.07 Restaurant Website
## Date:07.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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


  <section class="cards">
    <div class="card">
      <h2>Our New Menu</h2>
      <img src="menu.jpg" alt="Menu">
      <p>Discover our latest dishes crafted with fresh ingredients.</p>
  <a href="menu.html">See our menu</a>
    </div>
    <div class="card">
      <h2>Book a Table</h2>
      <img src=" tables.webp " alt="Book a Table">
      <p>Reserve your spot now and enjoy a fine dining experience.</p>
      <a href="contact.html">Book now</a>
    </div>
    <div class="card">
      <h2>Opening Hours</h2>
      <img src="open.jpg " alt="Opening Hours">
      <p>
        Mon - Fri: 2pm - 10pm <br>
        Sat: 2pm - 11pm <br>
        Sun: 2pm - 9pm
      </p>
    </div>
  </section>

  <footer>
    <p>Created by Kavinithan</p>
  </footer>
</body>
</html>

menu.html

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Little Lemon - Menu</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Our Menu</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="cards">
    <div class="card"><h2>Margherita Pizza</h2><img src="pizza.jpg"></div>
    <div class="card"><h2>Grilled Chicken</h2><img src="grilchiken.jpg"></div>
    <div class="card"><h2>Pasta Alfredo</h2><img src="veg.jpg"></div>
    <div class="card"><h2>Fresh juice</h2><img src="juice.jpg"></div>
    <div class="card"><h2>Burger & Fries</h2><img src="burger.jpg"></div>
    <div class="card"><h2>Paneer Tikka</h2><img src="panneer.jpg"></div>
    <div class="card"><h2>Fish Curry</h2><img src="fish.jpg"></div>
    <div class="card"><h2>Veggie Wrap</h2><img src="vegroll.jpg"></div>
    <div class="card"><h2>Chocolate Cake</h2><img src="cake.jpg"></div>
    <div class="card"><h2>Ice Cream Sundae</h2><img src="ice.jpg"></div>
    <div class="card"><h2>ICE fresh</h2><img src="ice2.jpg"></div>
  </section>

  <footer><p>Created by Kavinithan</p></footer>
</body>
</html>

admin.html

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title> BRAINROT - Administration</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Our Administration Team</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="cards">
    <div class="card"><img src=" boy1.jpg "><h2> Admin 1</h2><p>Manager</p></div>
    <div class="card"><img src=" boy2.jpg"><h2> Admin 2</h2><p>Head Chef</p></div>
    <div class="card"><img src=" boy3.jpg "><h2> Admin 3</h2><p>Assistant Chef</p></div>
    <div class="card"><img src=" boy4.jpg "><h2> Admin 4</h2><p>HR</p></div>

  </section>

  <footer><p>Created by Kavinithan</p></footer>
</body>
</html>

contact.html

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title> CASANDRA - Contact Us</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Contact Us</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="cards">
    <div class="card">
      <h2>Address:</h2>
      <p>  CASANDRA RESTAURANT<br>
         123 Food Street, Cityville, India</p>
    </div>
    <div class="card">
      <h2>Phone:</h2>
      <p>+91 7200247512</p>
    </div>
    <div class="card">
      <h2>Email:</h2>
      <p> ckavinithan@gmail.com</p>
    </div>
  </section>

  <footer><p>CREATED BY 
                   C KAVINITHAN(25011970)</p></footer>
</body>
</html>

style.css

body {
  font-family: Arial, sans-serif;
  margin: 0;
  
   
  background-image: url("background.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}

header {
  background-color: #333;
  padding: 20px;
  text-align: center;
  color: rgb(27, 8, 240);
}

header img {
  width: 100px;
}
p{
    font-size: 20px;
    font-weight: bold;
    font-style: italic;
    color: rgb(0, 64, 255);
}
nav {
  background-color: #444;
  display: flex;
  justify-content: center;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 14px 25px;
  font-weight: bold;
}

nav a:hover {
  background-color: #e67e22;
}

.banner {
  background: url("background.jpg") no-repeat center center/cover;
  padding: 80px 20px;
  color: rgb(235, 247, 7);
  text-align: center;
  font-size: 1.2em;
  position: relative;
}

.banner h1 {
  color: #e67e22;
  font-size: 2.5em;
  margin-bottom: 10px;
}

.cards {
   
  display: flex;
  justify-content: space-around;
  padding: 30px;
  flex-wrap: wrap;
  background-color: rgba(255, 255, 255, 0.8);
}

.card {
  background-color: #fff;
  border-radius: 10px;
  width: 30%;
  margin: 10px;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.card img {
  width: 100%;
  border-radius: 10px;
}

footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
div.card a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 15px;
  background-color: #e67e22;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}


```


## OUTPUT:
![alt text](<Screenshot 2025-10-06 213518.png>)
![alt text](<Screenshot 2025-10-06 213802.png>)
![alt text](<Screenshot 2025-10-06 213828.png>)
![alt text](<Screenshot 2025-10-07 085948.png>)
![alt text](<Screenshot 2025-10-07 090020.png>)
![alt text](<Screenshot 2025-10-06 213946.png>)
![alt text](<Screenshot 2025-10-06 214211.png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
