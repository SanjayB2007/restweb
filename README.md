# Ex.06 Restaurant Website
## Date:24-12-2025

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
rest.html

<html>
<head>
    <title>Welcome to Our Restaurant</title>
    <link rel="stylesheet" href="reststyle.css">
</head>
<body>

  
    <nav>
        <div>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact Us</a>
        </div>
    </nav>

   
    <div class="banner">
         <img src="icon.webp" width="250" height="200">
        <h1>Japanese restaurent</h1>
    </div>        

    <footer>
        <p>Designed by Sanjay Babu M &copy; 2025</p>
    </footer>

</body>
</html>

menu.html

<html>
<head>
    <title>Restaurant Menu</title>
    <link rel="stylesheet" href="menustyle.css">
</head>
<body>

    <header>
        <h1>Our Menu</h1>
        <p>Explore the flavors of our finest dishes</p>
    </header>

    <div class="container">
        <div class="menu-grid">
           
            <div class="menu-item">
                <img src="chicken tikka.webp" alt="chicken tikka">
                <div class="menu-item-content">
                    <h3>chicken tikka</h3>
                    <p class="price">Rs.200</p>
                </div>
            </div>


            <div class="menu-item">
                <img src="chilli prawns.webp" alt="chilli prawns">
                <div class="menu-item-content">
                    <h3>chilli prawns</h3>
                    <p class="price">Rs.120</p>
                </div>
            </div>

            
            <div class="menu-item">
                <img src="Egg65.jpg" alt="Egg65">
                <div class="menu-item-content">
                    <h3>Egg65</h3>
                    <p class="price">Rs.100</p>
                </div>
            </div>

            
            <div class="menu-item">
                <img src="fish pakoda.webp" alt="fish pakoda">
                <div class="menu-item-content">
                    <h3>fish pakoda</h3>
                    <p class="price">Rs.130</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="fried chicken.webp" alt="fried chicken">
                <div class="menu-item-content">
                    <h3>fried chicke</h3>
                    <p class="price">Rs.80</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="kebab chaat.webp" alt="kebab chaat">
                <div class="menu-item-content">
                    <h3>kebab chaat</h3>
                    <p class="price">Rs.150</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="lemon chicken.jpeg" alt="lemon chicken">
                <div class="menu-item-content">
                    <h3>lemon chicken</h3>
                    <p class="price">Rs.130</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="majestic chicken.webp" alt="majestic chicken">
                <div class="menu-item-content">
                    <h3>majestic chicken</h3>
                    <p class="price">Rs.180</p>
                </div>
            </div>
            </div>
            </div>
        </div>
    </div>

    <footer>
        <p>Designed by Sanjay Babu M &copy; 2025</p>
    </footer>

</body>
</html>

contact.html

><html>
    <head>
    <title>Contact Us</title>
</head>
<body>

    <header>
        <h1>Contact Us</h1>
        <p>We'd love to hear from you!</p>
        <link rel="stylesheet" href="contactstyle.css">
    </header>

    <div class="container">
        <div class="contact-info">
            <div>
                <h3>Visit Us</h3>
                <p>Japanese restaurent,25/7,shibuya street, bustling district,japan.</p>
            </div>
            <div>
                <h3>Call Us</h3>
                <p>3289529265</p>
            </div>
            <div>
                <h3>Email Us</h3>
                <p>japaneserest@gmail.com</p>
            </div>
        </div>
        <div class="contact-form">
            <h3>Send Us a Message</h3>
            <form action="#">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </div>

    </div>

    <footer>
        <p>Designed by Sanjay Babu M &copy; 2025</p>
    </footer>

</body>
</html>

reststyle.css

        body {
            margin: 0;
            background-color:rgb(248, 1, 1)
        }

     
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #c0ca04;
            padding: 10px 20px;
        }

        nav a {
            color: rgb(245, 10, 10);
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1em;
        }

        nav a:hover {
            color: #cd891b;
        }

        .banner {
            height: 100vh;
            background: url('image.jpg') no-repeat center center/cover;
            color: rgb(192, 160, 160);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }

        .banner h1 {
            font-size: 4em;
            margin: 0;
            text-shadow: 2px 2px 5px rgba(85, 204, 21, 0.7);
        }

        .banner p {
            font-size: 1.5em;
            margin: 20px 0;
            max-width: 600px;
            line-height: 1.5;
        }

        .banner a {
            padding: 15px 30px;
            background-color: #f31212;
            color: rgb(227, 17, 17);
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .banner a:hover {
            background-color: #00d315;
        }

        footer {
            background-color: #121111;
            color: rgb(200, 17, 17);
            text-align: center;
            padding: 15px;
            font-size: 1em;
        }

menustyle.css

        body {
            margin: 0;
            padding: 0;
            background-color: #ba1717;
        }

        header {
            background-color:rgb(22, 198, 52);
            color: rgb(166, 12, 12);
            text-align: center;
            padding: 40px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 10px 0;
            font-size: 1.2em;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .menu-item {
            background-color: rgb(156, 17, 17);
            border-radius: 8px;
            box-shadow: 0 4px 8px rgb(0, 0, 0);
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgb(0, 0, 0);
        }

        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .menu-item-content {
            padding: 15px;
            text-align: center;
        }

        .menu-item-content h3 {
            margin: 10px 0;
            font-size: 1.5em;
            color: #333333ac;
        }

        .menu-item-content p {
            margin: 5px 0;
            font-size: 1em;
            color: #66666661;
        }

        .menu-item-content .price {
            font-size: 1.2em;
            color: #d30000;
            font-weight: bold;
        }

        footer {
            background-color: #000000;
            color: rgb(200, 11, 11);
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }

contactstyle.css

        body {
            margin: 0;
            padding: 0;
            background-color: #090978;
        }

        header {
            background-color:rgb(244, 240, 240);
            color: rgb(8, 3, 108);
            text-align: center;
            padding: 30px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 10px 0;
            font-size: 1.2em;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .contact-info, .contact-form {
            background-color: rgb(5, 7, 134);
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgb(250, 249, 249);
        }

        .contact-info {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .contact-info div {
            flex: 1;
        }

        .contact-info h3 {
            margin: 0;
            color:rgb(255, 255, 255);
        }

        .contact-info p {
            margin: 5px 0;
            font-size: 1.1em;
        }

        .contact-info img {
            width: 80px;
            height: 80px;
        }

        .contact-form h3 {
            margin-bottom: 20px;
            color: #148df0;
        }

        .contact-form form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .contact-form input, .contact-form textarea {
            padding: 10px;
            border: 1px solid #2a0bb5;
            border-radius: 5px;
            font-size: 1em;
            width: 100%;
        }

        .contact-form button {
            padding: 10px;
            background-color:rgb(255, 255, 255);
            color: rgb(37, 11, 133);
            border: none;
            border-radius: 5px;
            font-size: 1em;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color:rgb(248, 242, 242);
        }

        footer {
            background-color: #08c6c3;
            color: rgb(16, 8, 170);
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }

```

## OUTPUT:
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (30).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
