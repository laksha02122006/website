# Ex.07 Restaurant Website
## Date:17/5/25

Name:- V.B.Laksha

Reg.no:-212224220051

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

exp7web.html

~~~
<!DOCTYPE html>
<html>
<head>
  <title>Restaurant Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="top-box">KIMCHI KLASSIC</div>
   
  <nav class="nav-bar">
    <ul>
      <li><a href="menu.html" class="nav-link">Menu</a></li>
      <li><a href="gallery.html" class="nav-link">Gallery</a></li>
      <li><a href="contact.html" class="nav-link">Contact Us</a></li>
      <li><a href="administration.html" class="nav-link">Administration</a></li>
    </ul>
  </nav>
      <div class="food-item">
         <img src="food5.jpg" alt="Kongguksu">
        <h3>30% OFF THIS WEEKEND</h3>
    
      </div>
      <div class="food-item">
         <img src="mochi.image.jpg" alt="Kongguksu">
        <h3>CHECK OUT OUR NEW MENU</h3>
  
      </div>
  



</body>
</html>

<style>


body {
  background-color: burlywood;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-image: url(bgimage.jpg);
  
  margin: 0;
}



.top-box{
  background-color: #53504f;
  height:110px ;
  width: 100%;
  font-style: italic;
  font-weight: 300;
  font-size: 100px;
  text-align: center;
  text-shadow: 2px 2px #5c3b1f;
  box-shadow: 0px 0px 10px rgba(223, 27, 27, 0.5);
  color:#dd731b;

  
}
nav {
            background-color: #f1ebeb;
            padding: 10px ;
            text-align: center;
        }

        nav ul { background-color: rgb(16, 17, 17);
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #dd731b;
        }

        /* Menu Section Styles */
        .container {
            padding: 20px;
            text-align: center;
            flex-grow: 1;
        }

        h2 {
            font-size: 32px;
            color: #f7f0f0;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }
        h3{
          color: #f1ebeb;
        }

</style>
~~~

administration.html

~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        nav {
            background-color: #333;
            padding: 10px ;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #dd731b;
        }

        /* Menu Section Styles */
        .container {
            padding: 20px;
            text-align: center;
            flex-grow: 1;
        }

        h2 {
            font-size: 32px;
            color: #333;
        }

        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .food-item {
            background-color: rgb(167, 165, 167);
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 30%;
            max-width: 300px;
            transition: transform 0.3s ease-in-out;
        }

        .food-item img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 10px;
        }

        .food-item h3 {
            font-size: 24px;
            color: #333;
        }

        .food-item p {
            font-size: 16px;
            color: #555;
            line-height: 1.5;
        }

        .food-item:hover {
            transform: scale(1.05);
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
            width: 100%;
            position: relative;
            bottom: 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="nav-bar">
        <ul>
            <li><a href="restaurant.html" class="nav-link">Home</a></li>
            <li><a href="menu.html" class="nav-link">Menu</a></li>
            <li><a href="gallery.html" class="nav-link">Gallery</a></li>
            <li><a href="contact.html" class="nav-link">Contact Us</a></li>
            <li><a href="administration.html" class="nav-link">Administration</a></li>
        </ul>
    </nav>

    <!-- Menu Section -->
    <div class="container">
        <h2>Administration</h2>
        <div class="menu-items">
            <div class="food-item">
                <img src="chef9.jpg" alt="general manager">
                <h3>Rattish <br> General Manager</h3>
                
            </div>
            <div class="food-item">
                <img src="chef2.jpg" alt="head chef">
                <h3>Victor <br> Head Chef</h3>
                
            </div>
            <div class="food-item">
                <img src="chef3.jpg" alt="Sous chef">
                <h3>Frederick <br> Sous Chef</h3>

            </div>
            <div class="food-item">
                <img src="chef4.jpg" alt="Seolleongtang">
                <h3>James<br> Restaurant Supervisor</h3>

            </div>
            <div class="food-item">
                <img src="chef4.png" alt="Tteokbokki">
                <h3>David <br> Marketing Manager</h3>

            </div>
            <div class="food-item">
                <img src="chef5.jpg" alt="Haemul Pajeon">
                <h3>Mobina <br> Finance Manager</h3>
               

        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>V.B.Laksha</p>
    </footer>
</body>
</html>
~~~

menu.html

~~~

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        nav {
            background-color: #333;
            padding: 10px ;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #dd731b;
        }

        /* Menu Section Styles */
        .container {
            padding: 20px;
            text-align: center;
            flex-grow: 1;
        }

        h2 {
            font-size: 32px;
            color: #333;
        }

        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .food-item {
            background-color: rgb(167, 165, 167);
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 30%;
            max-width: 300px;
            transition: transform 0.3s ease-in-out;
        }

        .food-item img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 10px;
        }

        .food-item h3 {
            font-size: 24px;
            color: #333;
        }

        .food-item p {
            font-size: 16px;
            color: #555;
            line-height: 1.5;
        }

        .food-item:hover {
            transform: scale(1.05);
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
            width: 100%;
            position: relative;
            bottom: 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="nav-bar">
        <ul>
            <li><a href="restaurant.html" class="nav-link">Home</a></li>
            <li><a href="menu.html" class="nav-link">Menu</a></li>
            <li><a href="gallery.html" class="nav-link">Gallery</a></li>
            <li><a href="about.html" class="nav-link">About</a></li>
            <li><a href="administration.html" class="nav-link">Administration</a></li>
        </ul>
    </nav>

    <!-- Menu Section -->
    <div class="container">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="food-item">
                <img src="food1.jpg" alt="Kongguksu">
                <h3>Kongguksu</h3>
                <p>Kongguksu is a textured noodle dish with a subtle flavor of beans, eaten in summer.</p>
            </div>
            <div class="food-item">
                <img src="food2.jpg" alt="Jjajangmyeon">
                <h3>Jjajangmyeon</h3>
                <p>Jjajangmyeon is a Korean version of Chinese noodles with a savory black bean paste sauce.</p>
            </div>
            <div class="food-item">
                <img src="food3.jpg" alt="Bibimbap">
                <h3>Bibimbap</h3>
                <p>Bibimbap is a famous Korean dish consisting of rice, vegetables, and a spicy sauce, usually topped with an egg.</p>
            </div>
            <div class="food-item">
                <img src="food4.jpg" alt="Seolleongtang">
                <h3>Seolleongtang (Ox Bone Soup)</h3>
                <p>This winter soup is made from ox bones and beef bones boiled for hours, resulting in a rich, white-colored broth.</p>
            </div>
            <div class="food-item">
                <img src="food5.jpg" alt="Tteokbokki">
                <h3>Tteokbokki (Spicy Red Rice Cake)</h3>
                <p>Steamed rice cakes mixed with fish cakes and scallions in a spicy chili paste and soybean sauce.</p>
            </div>
            <div class="food-item">
                <img src="food6.jpg" alt="Haemul Pajeon">
                <h3>Haemul Pajeon (Seafood Vegetable Pancake)</h3>
                <p>This crispy pancake is made with rice and egg batter, mixed with a variety of seafood and green onions.</p>
            </div>
            <div class="food-item">
                <img src="food7.jpg" alt="Samgyeopsal">
                <h3>Samgyeopsal (Korean BBQ)</h3>
                <p>Thick slices of pork belly grilled at your table and served with sesame oil, garlic, and onion wrapped in lettuce.</p>
            </div>
            <div class="food-item">
                <img src="food8.jpg" alt="Soy Sauce Crab">
                <h3>Soy Sauce Crab</h3>
                <p>Crab marinated in soy sauce, offering a tangy and bitter taste, typically served cold.</p>
            </div>
            <div class="food-item">
                <img src="food9.jpg" alt="Japchae">
                <h3>Japchae</h3>
                <p>Glass noodles stir-fried in sesame oil with beef, mushrooms, and a variety of vegetables.</p>
            </div>
            <div class="food-item">
                <img src="food10.jpg" alt="Patbingsu">
                <h3>Patbingsu</h3>
                <p>A popular dessert made with ice shavings, sweet toppings like fruits, red beans, and condensed milk.</p>
            </div>
            <div class="food-item">
                <img src="food11.jpg" alt="Kimchi Mandu">
                <h3>Kimchi Mandu</h3>
                <p>Delicious Korean dumplings filled with spicy kimchi and vegetables, offering a perfect balance of flavors.</p>
            </div>
            <div class="food-item">
                <img src="food12.jpg" alt="Sundubu Jjigae">
                <h3>Sundubu Jjigae</h3>
                <p>A spicy soft tofu stew made with tofu, vegetables, meat, seafood, and topped with a raw egg.</p>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>V.B.Laksha</p>
    </footer>
</body>
</html>
~~~

gallery.html

~~~

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Images with Same Size</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .nav-bar {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        .nav-bar ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        .nav-bar ul li {
            display: inline-block;
            margin-right:20px;
        }

        .nav-bar ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        
        nav ul li a:hover {
            background-color: #dd731b;
        }

        h1 {
            text-align: center;
            margin-top: 30px;
            color: #333;
        }

        .image-container {
            display: flex;
            justify-content: space-between;
            gap: 10px; /* Space between images */
            padding: 20px;
            flex-wrap: wrap; /* To ensure images wrap if the screen is smaller */
        }

        .image-container img {
            width: 23%; /* Fixed width for each image, allowing for some space between */
            height: auto; /* Maintain aspect ratio */
            border-radius: 8px;
            margin-bottom: 10px;
            object-fit: cover; /* Ensures the image fits the container without stretching */
        }

    </style>
</head>
<body>

    <!-- Top Navigation Bar -->
    <nav class="nav-bar">
        <ul>
            <li><a href="restaurant.html" class="nav-link">Home</a></li>
            <li><a href="menu.html" class="nav-link">Menu</a></li>
            <li><a href="gallery.html" class="nav-link">Gallery</a></li>
            <li><a href="contact.html" class="nav-link">Contact Us</a></li>
            <li><a href="administration.html" class="nav-link">Administration</a></li>
        </ul>
    </nav>

    <!-- Gallery Title -->
    <h1>Gallery</h1>

    <!-- Image Gallery Container -->
    <div class="image-container">
        <img src="galleray.1.jpg" alt="Image 1">
        <img src="galleray.2.jpg" alt="Image 2">
        <img src="galleray.3.jpg" alt="Image 3">
        <img src="galleray.4.jpg" alt="Image 4">
    </div>

    <!-- Bottom Navigation Bar -->
    
</body>
</html>
~~~

## OUTPUT:

![Screenshot 2025-05-17 113616](https://github.com/user-attachments/assets/75f67bdf-00ac-4d3a-925b-3e4b4341333d)

![Screenshot 2025-05-17 113616](https://github.com/user-attachments/assets/7ee98293-ceb4-4b5b-94cf-67571b79b08c)

![Screenshot 2025-05-17 113704](https://github.com/user-attachments/assets/0f69868b-10fc-4f62-92f6-b7b8b50a63c2)

![Screenshot 2025-05-17 113723](https://github.com/user-attachments/assets/1b6f992d-a527-4766-9743-db6852bdb5d2)

![Screenshot 2025-05-17 113738](https://github.com/user-attachments/assets/54dd0262-90a6-4ccb-8fc5-7ef4e4e7f5f5)

![Screenshot 2025-05-17 113757](https://github.com/user-attachments/assets/b3adcde2-a41b-4357-91d5-8fcff7fba3ed)

![Screenshot 2025-05-17 113844](https://github.com/user-attachments/assets/9fc50224-ba82-47cc-9bed-cd937bda2653)


![Screenshot 2025-05-17 113857](https://github.com/user-attachments/assets/21facab4-2332-4d80-97b0-5c5d6bd542d7)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
