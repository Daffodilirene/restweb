# Ex.06 Restaurant Website
## Date:26.12.2025

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
home.html

<html>
<head>
    <title>Home</title>
    <link rel="stylesheet" href="home.css">
</head>
<body>

<div class="navbar">
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
</div>
<br>
<br>
<br>

<br>
<br>
<p align="center">
<h1 align="center" >Elite Brew House</h1>
<p class="tagline" align="center"> Coffee,crafted for the elite A small coffee shop can be a world of its own &minus; an intimate setting where the aroma of freshly brewed coffee mingles with quiet conversation and the soft clink of mugs. These spaces, often tucked away in neighborhoods or side streets, offer more than just caffeine; they provide a warm and inviting atmosphere where regulars find comfort and new visitors discover a sense of belonging. For a writer, a coffee shop is a perfect setting to explore character interactions, daily routines, 
    or a quiet escape from the chaos of the outside world.From  Every detail, from the barista&#39;s smile to the sound of steamed milk, contributes to the feeling that time slows down here. Whether you&#39;
re writing a scene of quiet reflection, a serendipitous meeting, or the buzz of a busy morning, these 60 ways to describe a small coffee shop will help you capture its charm, coziness, and rich sensory experience.</p>
<div class="footer">
    <h3>Designed by Daffodil Irene (25002685)</h3>
</div> 

</body>
</html>


home.css


body{
    margin:0;
    background:url("home.jpg");
    background-size:cover;
    color: white;   
    font-family:Arial;
}

.navbar{
    background:#eef3ff;
    padding:10px;
    text-align:right;
}
.navbar a{
    margin:15px;
    text-decoration:none;
    color:purple;
    font-weight:bold;
}

h1{
    font-size:80px;
    margin:60px;
    color:rgb(14, 15, 15);
}

.tagline{
    margin-left:60px;
    font-size:30px;
    color:white;
}
.footer{
    background:#f0eded;
    margin-top:250px;
    padding:.5px;
    text-align:center;
    color:black;
}   



menu.html


<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>

<div class="navbar">
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
</div>

<h1 class="title">MENU</h1>

<div class="card-container">
    <div class="card">
        <img src="espresso.jpg">
        <h3>Espresso</h3>
        <p>Rs. 190</p>
    </div>
    <div class="card">
        <img src="cappuccino.jpg">
        <h3>Cappuccino</h3>
        <p>Rs. 250</p>
    </div>
    <div class="card">
        <img src="caramel.jpg">
        <h3>Caramel</h3>
        <p>Rs. 230</p>  
    </div>
    <div class="card">
        <img src="filter.jpg">
        <h3>Filter</h3>
        <p>Rs. 110</p>    
    </div> 
    <div class="card">
        <img src="coldcoffe.jpg">
        <h3>Cold Coffee</h3>
        <p>Rs. 270</p>  
    </div>
</div>
<div class="footer">
    <h3>Designed by Daffodil Irene (25002685)</h3>
</div>       
</body>

</html>



menu.css

body{
    margin:0;
    background:url("menu.jpg");
    background-size:cover;
    color: white;
    font-family:Arial;
}

.navbar{
    background:#ebebf0;
    padding:5px;
    text-align:right;
}
.navbar a{
    margin:10px;
    text-decoration:none;
    color:purple;
    font-weight:bold;
}

.title{
    color:white;
    font-size:70px;
    margin:35px;
}

.card-container{
    display:flex;
    gap:50px;
    margin-left:150px;
}

.card{
    background:#121212;
    width:160px;
    padding:15px;
    border-radius:15px;
    text-align:center;
}

.card img{
    width:100%;
    border-radius:10px;
}
.footer{
    background:#f0eded;
    margin-top: 250px;
    padding:.5px;
    text-align:center;
    color:black;
}

contact.html

<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>

<div class="navbar">
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
</div>

<h1 align=center>CONTACT</h1>

<div class="contact-box" ALIGN="center">
    <p><b>Visit us:</b><BR><br>Elite Brew House<br>India</p>
    <p><b>Phone:</b> +91 7339259406</p>
    <p><b>Email:</b> EliteBrewHouse28@gmail.com</p>
</div>
<div class="footer">
    <h3>Designed by Daffodil Irene (25002685)</h3>
</div> 
</body>
</html>     


contact.css

body{
    margin:0;
    background:url("contact.jpg");
    background-size:cover;
    color:white;
    font-family:Arial;
}

.navbar{
    background:#eef3ff;
    padding:10px;
    text-align:right;
}
.navbar a{
    margin:10px;
    text-decoration:none;
    color:purple;
    font-weight:bold;
}
h1{
    color:white;
    font-size:70px;
    margin:40px;
    align-content:center;
}

.contact-box{
    margin-left:40px;
    font-size:10px;
    color: rgb(248, 240, 255);
    align-content: center;
}
.footer{
    background:#f0eded;
    margin-top: 250px;
    padding:.5px;
    text-align:center;
    color:black;
}


admin.html


<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>

<div class="navbar">
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
</div>

<h1 class="title">ADMINISTRATION TEAM</h1>

<div class="card-container">
    <div class="card">
        <img src="myphoto2.jpeg">
        <h3>Daffodil Irene.S</h3>
        <p>Founder & Managing Director</p>
    </div>
    <div class="card">
        <img src="manager.jpg">
        <h3>Surya</h3>
        <p>cafe Manager</p>
    </div>
    <div class="card">
        <img src="customerrelationsmanager.jpg">
        <h3>Joe Kerry</h3>
        <p>customer relations manager</p>
         
    </div>
    <div class="card">
        <img src="Headbarista.jpg">
        <h3>Kim Namjoon</h3>
        <P>Head Barista</P>
            
    </div>
</div>    
<div class="footer">
    <h3>Designed by Daffodil Irene (25002685)</h3>
</div>     
  
</body>
</html>



admin.css


body{
    margin:0;
    background:url("admin.jpg");
    background-size:cover;
    color: white;
    font-family:Arial;
}

.navbar{
    background:#ebebf0;
    padding:5px;
    text-align:right;
}


.navbar a{
    margin:10px;
    text-decoration:none;
    color:purple;
    font-weight:bold;
}

.title{
    color:white;
    font-size:70px;
    margin:35px;
}

.card-container{
    display:flex;
    gap:50px;
    margin-left:150px;
}

.card{
    background:#121212;
    width:160px;
    padding:15px;
    border-radius:15px;
    text-align:center;
}

.card img{
    width:100%;
    border-radius:10px;
}
.footer{
    background:#f0eded;
    margin-top:250px;
    padding:.5px;
    text-align:center;
    color:black;
}


























```


## OUTPUT:
![alt text](<Screenshot (42)-1.png>)


![alt text](<Screenshot (43)-1.png>)


![alt text](<Screenshot (44).png>)


![alt text](<Screenshot (45).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
