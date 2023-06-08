# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

## PROGRAM :

### sample.html
```
<!DOCTYPE html>
<html>
<head>
	<title>Delicious Restaurant - Home</title>
	<link rel="stylesheet" type="text/css" href="./css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Teko&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Teko&family=Tilt+Prism&display=swap" rel="stylesheet">
<link rel="icon" href="./assets/logo.png" type="image/x-icon" />
</head>
<body>
    
	<header>
		<nav>
			<ul>
				<li><a href="sample.html">Home</a></li>
				<li><a href="product.html">Menu</a></li>
				<li><a href="contact.html">Contact</a></li>
                
			</ul>
            <!-- <div class="logo"> <img src="./assets/logo.png"></div> -->
		</nav>
        
           
        </li>
	</header>
    
	<main>
        <div class="content">
		<h1>Welcome to Delicious Restaurant</h1>
		<p>Discover our exquisite menu and enjoy a unique dining experience.</p>
		<img src="./assets/o1.jpg" alt="Delicious Restaurant">
        <h3>NOW ACCEPTING INQUIRIES FOR PRIVATE EVENTS & HOLIDAY PARTIES!</h3>
        <p>We are now accepting all inquiries for full buyouts for private events and holiday parties, any day of the week, day or night.<br> Our restaurant can accommodate up to 45 guests and potentially more.<br> We can work with you on the menu, and curate beverages, beer, wine, and sake as well.<br> Please contact us here to inquire!</p>
        <h3>DINNER RESERVATIONS!</h3>
        <p>We are now open for dinner service Thursday through Sunday! We’ll be accepting limited walk-ins and reservations on Yelp. 

            For brunch, we still do not take reservations as we seat guests on a first come first serve basis. However, you can join our Yelp! Waitlist to save your spot ahead of time (same day only)!</p>
            <img src="./assets/main.jpg">
            <h3>BUSINESS HOURS</h3>
            <p>BRUNCH: Thursday through Monday 9:00am - 2:30pm</p>

               <p> DINNER: Thursday through Sunday 5:00pm - 9:00pm</p>
                
                <p>CLOSED Tuesdays & Wednesdays</p> 
                
               <p> Dine-in, takeout, and delivery (via DoorDash) available</p>
            </div>
        </main>

	<footer>
		<p>&copy; 2023 Delicious Restaurant</p>
	</footer>
</body>
</html>
```
### product.html
```
<!DOCTYPE html>
<html>
<head>
	<title>Delicious Restaurant - Menu</title>
	<link rel="stylesheet" type="text/css" href="./css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Teko&family=Tilt+Prism&display=swap" rel="stylesheet">
<link rel="icon" href="./assets/logo.png" type="image/x-icon" />
</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="sample.html">Home</a></li>
				<li><a href="product.html">Menu</a></li>
				<li><a href="contact.html">Contact</a></li>
			</ul>
            <!-- <div class="logo"> <img src="./assets/logo.png"></div> -->
		</nav>
	</header>
	<main>
		<div class="content">
            <div class="productcontent">    
              <h1>OUR MENU</h1>
              <div class="productitems">
                  <div class="productitem"> 
                      <div class="itemimage">
                      <img src="./assets/nodle.avif" alt="product image">
                      </div>
                      <div class="itemname">NOODLES</div>
                      <div class="itemprice">Price: Rs.395/- </div>
                  </div>
                  <div class="productitem"> 
                      <div class="itemimage">
                      <img src="./assets/pasta.avif"  alt="product image">
                      </div>
                      <div class="itemname">PASTA</div>
                      <div class="itemprice">Price: Rs.450/- </div>
                  </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="./assets/pizza.webp"  alt="product image">
                    </div>
                    <div class="itemname">PIZZA</div>
                    <div class="itemprice">Price: Rs.470/- </div>
                  </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="./assets/sanwidch.jpg"  alt="product image">
                    </div>
                    <div class="itemname">SANDWIDCH</div>
                    <div class="itemprice">Price: Rs.599/- </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./assets/staek.avif"  alt="product image">
                  </div>
                  <div class="itemname">STEAK</div>
                  <div class="itemprice">Price: Rs.850/- </div>
              </div>  <div class="productitem"> 
                <div class="itemimage">
                <img src="./assets/icecream.jpg"  alt="product image">
                </div>
                <div class="itemname">ICE CREAM</div>
                <div class="itemprice">Price: Rs.970/- </div>
            </div>
	</main>
	<footer>
		<p>&copy; 2023 Delicious Restaurant</p>
	</footer>
</body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html>
<head>
	<title>Delicious Restaurant - Contact</title>
	<link rel="stylesheet" type="text/css" href="./css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Teko&family=Tilt+Prism&display=swap" rel="stylesheet">
<link rel="icon" href="./assets/logo.png" type="image/x-icon" />

</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="sample.html">Home</a></li>
				<li><a href="product.html">Menu</a></li>
				<li><a href="contact.html">Contact</a></li>
			</ul>
            <!-- <div class="logo"> <img src="./assets/logo.png"></div> -->
		</nav>
	</header>
	<main>
    <div class="content">
		<h1>Contact Us</h1>
		<p>Feel free to contact us with any questions or feedback.</p>
		<form action="#" method="post">
			<label for="name">Name:</label>
			<input type="text" id="name" name="name" placeholder="Your name" required>
			<label for="email">Email:</label>
			<input type="email" id="email" name="email" placeholder="Your email" required>
			<label for="message">Message:</label>
			<textarea id="message" name="message" placeholder="Your message" rows="5" required></textarea>
			<input type="submit" value="Submit">
		</form>
    </div>
	</main>
	<footer>
		<p>&copy; 2023 Delicious Restaurant</p>
	</footer>
</body>
</html>
```

## OUTPUT:

### Server Output:
![ex9 web server output](https://github.com/Priya-Loganathan/productcompanywebsite/assets/121166075/775b540e-8a91-4500-a17a-5906836bbbb8)
### Home Page:
![ex9 web home](https://github.com/Priya-Loganathan/productcompanywebsite/assets/121166075/a990f020-7444-4075-b380-071133e568b4)
### Product Page:
![ex9 web product](https://github.com/Priya-Loganathan/productcompanywebsite/assets/121166075/986c9de5-ec79-401d-8af3-97ca512dd8a1)
### Contact Page:
![ex9 web contact](https://github.com/Priya-Loganathan/productcompanywebsite/assets/121166075/2700e556-89d0-47cc-9a5d-44b51cfcc2cc)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
