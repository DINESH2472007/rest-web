# Ex.07 Restaurant Website
## Date:25/12/2024

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


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TUNTUN RESTAURANT</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Delius&family=Pacifico&family=Quicksand:wght@300..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: "Quicksand", sans-serif;
    font-optical-sizing: auto;
    font-weight: 10;
    font-style: bold;
}

.background {
    position: fixed;
    inset: 0;
    background-image: url("https://i.pinimg.com/236x/6b/7c/3a/6b7c3af7f32ed3fea9f7dbf47785c4bd.jpg");
    background-size: cover;
    background-position: center;
    z-index: -1;
    filter: blur(4px);
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #f3d9aa;
    padding: 10px 20px;
}

.navbar img{
    display: flex;
    height: 70px;
    width: 40px;
}

.navbar .logo {
    color: #000000;
    font-size: 3em;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 15px;
}

.nav-links li {
    display: inline;
    font-size: 1.5em;
}

.nav-links a {
    color: green;
    text-decoration: none;
    padding: 8px 15px;
    transition: background 0.3s;
}

.nav-links a:hover {
    background-color: #ffffffbe;
    border-radius: 4px;
}

.menu-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
    margin-top: 60px;
    justify-content: center;
}

.card {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    overflow: hidden;
    width: 300px;
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}

.card-content {
    padding: 15px;
    text-align: center;
}

.card-content h3 {
    font-size: 1.25em;
    margin-bottom: 10px;
    color: #333;
}

.card-content p {
    font-size: 0.9em;
    color: #777;
    margin-bottom: 10px;
}

.price {
    display: block;
    font-size: 1.1em;
    font-weight: bold;
    color: #e67e22;
}

</style>
    <div class="background"></div>

    <nav class="navbar">
        <div class="logo"> TUNTUN Restaurant</div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="bg">
        <div class="menu-container">
            <div class="card">
                <img src="https://i.pinimg.com/236x/c2/ab/8b/c2ab8b5591674a253d7d566cae43d763.jpg" alt="Briyani">
                <div class="card-content">
                    <h3>Briyani</h3>
                    <p>Crispy and Yummy Briyani.</p>
                    <span class="price">Rs. 110</span>
                </div>
            </div>
            
            <div class="card">
                <img src="https://images.pexels.com/photos/28674705/pexels-photo-28674705/free-photo-of-indian-dal-and-rice-in-traditional-utensils.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Dal Rice">
                <div class="card-content">
                    <h3>Dal Rice</h3>
                    <p>Traditional Indian Dal and Rice.</p>
                    <span class="price">Rs. 50</span>
                </div>
            </div>
        
            <div class="card">
                <img src="https://images.pexels.com/photos/20422135/pexels-photo-20422135/free-photo-of-meal-on-plate-and-sauces.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Vada">
                <div class="card-content">
                    <h3>Vada</h3>
                    <p>Crispy and Crunchy Vada.</p>
                    <span class="price">Rs. 10</span>
                </div>
            </div>
        </div>
        <div class="menu-container">
            <div class="card">
                <img src="https://images.pexels.com/photos/29333631/pexels-photo-29333631/free-photo-of-warm-ceramic-coffee-cup-on-marble-surface.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Coffee">
                <div class="card-content">
                    <h3>Coffee</h3>
                    <p>A delightful Coffee.</p>
                    <span class="price">Rs. 10</span>
                </div>
            </div>
            
            <div class="card">
                <img src="https://images.pexels.com/photos/20689160/pexels-photo-20689160/free-photo-of-flat-bread-and-elephant-figurine.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Chappathi">
                <div class="card-content">
                    <h3>Chappathi</h3>
                    <p>Soft Chapathi.</p>
                    <span class="price">Rs. 15</span>
                </div>
            </div>
        
            <div class="card">
                <img src="https://images.pexels.com/photos/2456435/pexels-photo-2456435.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Noodles">
                <div class="card-content">
                    <h3>Noodles</h3>
                    <p>Nice and long Noodles.</p>
                    <span class="price">Rs. 100</span>
                </div>
            </div>
        </div>
    </div>
    
</body>
</html>





```
## OUTPUT:

![alt text](<web ex -7 .png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
