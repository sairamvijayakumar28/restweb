# Ex.07 Restaurant Website
## Date:05-10-2025

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
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contanct.html">Contanct</a>
        </nav>
        <div class="name">
            <h1>SAIR RESTAURANT</h1>
            <b>"From Field To Fork -Fresh Every Season"</b>
        </div>
        <div class="offer">
            <h2>Limited Offer</h2>
            <h3>50% off for all Sea Food</h3>
        </div>
    
        <footer>
            <h6 class="bottom">SAIRAM.V (25012434)</h6>

        </footer>
    </body>
</html>
home.css
body{
    background-image:url(red-brown-restaurant.jpg);
    background-position: center;
    background-size:cover;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: bisque;
    background-repeat: no-repeat;
}

a{
    padding: 15px;
    color:rgb(214, 155, 5);
    position: relative;
    left: 1100px;
    top: 20px;
}
a:hover{
    background-color: aquamarine;
    color:blue;
}
.name{
    text-align: center;
    position: relative;
    left: 295px;
    top:20px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
    color:  rgb(165, 157, 157);
    font-size: 30px;
    width: 1000px;
   
}

.offer{
    text-align: right;
    font-size: 40px;
    color: rgb(165, 157, 157);
    position: relative;
    right: 100px;
    top:200px;

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 190px;
    background-color: brown;
}
menu.html
<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="menu.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contanct.html">Contanct</a>
        </nav>
        <h1>Menu Lists</h1>
        <div class="main">
            <div class="food1">
                <img src="1.jpg"alt="pic">
                <b>Meatloaf-$60</b>
            </div>
            <div class="food2">
                <img src="2.jpg" alt="pic">
                <b>Salmon Fry-$15</b>
            </div>
            <div class="food3">
                <img src="3.jpg" alt="pic">
                <b>Yakitori-$50</b>
            </div>
            <div class="food4">
                <img src="4.jpg" alt="pic">
                <b>Shrimp soup-$60</b>
            </div>
            <div class="food5">
                <img src="5.jpg" alt="pic">
                <b>sushi-$30</b>
            </div>
            <div class="food6">
                <img src="6.jpg" alt="pic">
                <b>Shellsushi-$60</b>
            </div>
            <div class="food7">
                <img src="7.jpg" alt="pic">
                <b>Shellfish-$60</b>
            </div>
            <div class="food8">
                <img src="8.jpg" alt="pic">
                <b>Pizza-$5</b>
            </div>
            <div class="food9">
                <img src="9.jpg" alt="pic">
                <b>Italian Shrimp-$60</b>
            </div>
            <div class="food10">
                <img src="10.jpg" alt="pic">
                <b>Crab Fry-$60</b>
            </div>
            <div class="food11">
                <img src="11.jpg" alt="pic">
                <b>-shrimp Skewers-$60</b>
            </div>
            <div class="food12">
                <img src="12.jpg" alt="pic">
                <b>Noodles-$60</b>
            </div>
        </div>
         <footer>
            <h6 class="bottom">SAIRAM.V (25012434)</h6>

        </footer>
    </body>
</html>
menu.css
body{
    
    background:url(pexels-pixabay-276147.jpg);
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
}

a{
    padding: 15px;
    color:rgb(227, 144, 0);
    position: relative;
    left: 1100px;
    top: 20px;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
.food1{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
}
.food2{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
    
}
.food3{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
}
.food4{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
    
}
.food5{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    bottom: 20px;
    
}
.food6{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food7{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food8{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food9{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food10{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food11{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    top: 10px;
    
}
.food12{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    top: 10px;
}
img{
    width: 170px;
    height: 100px;
    
}
h1{
    text-align: center;
    position: relative;
    bottom: 20px;
    left:600px;
    padding: 10px;
    background-color: rgba(107, 83, 32, 0.951);
    color: rgb(184, 170, 170);
    width:200px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: brown;
    position: relative;
    top: 30px;
}
admin.html
<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="admin.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contanct.html">Contanct</a>
        </nav>
        <h1>Administration</h1>
        <div class="admin">
            <div class="a1">
                <img src="my pic.jpg">
                <b>Sair</b>
                <p>CEO</p>
            </div>
            <div class="a2">
                <img src="ajith.jpg">
                <b>Ajith</b>
                <p>Reception</p>
            </div>
            <div class="a3">
                <img src="vijay.jpg">
                <b>Leo</b>
                <p>Service Manager</p>
            </div>
            <div class="a4">
                <img src="mrunal.jpg">
                <b>Mrunal Thahur</b>
                <p>Manager</p>
            </div>
            <div class="a5">
                <img src="sam.jpg">
                <b>Samantha</b>
                <p>Accounts Manager</p>
            </div>
            <div class="a6">
                <img src="kalyani.jpg">
                <b>Kalyani Priyadarshan</b>
                <p>Maintenance Manager</p>
            </div>
        </div>
        <footer>
            <h6 class="bottom">SAIRAM.V (25012434)</h6>
        </footer>
    </body>
</html>
admin.css
body{
    background-image: url(pexels-lazybird-1260727.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
a{
    padding: 15px;
    color:rgb(145, 119, 4);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
    font-size: x-large;
}
.admin{
    display: grid;
    grid-template-columns: repeat(6,1fr);
    font-size: 20px;
    gap:10px;
}
img{
    width: 210px;
    height: 300px;
    border:solid 5px rgb(240, 235, 235);
}
.a1,.a2,.a3,.a4,.a5,.a6{
    padding: 5px;
    background-color: antiquewhite;
    text-align: center;
    font-size: 24px;
    
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: rgba(44, 35, 35, 0.632);
    position: relative;
    top: 60px;
    color:white;
}
h1{
    text-align: center;
    color:white;
    font-size: 40px;
}
contanct.html
<html>
    <head>
        <title>Contanct</title>
        <link rel="stylesheet" href="contanct.css">
    </head>
    <body>
         <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contanct.html">Contanct</a>
        </nav>
        <div class="contanct-container">
            <h1>Contact Us:</h1>
            <h4>Address:200 S Casino Dr, Laughlin, NV 89029, United States</h4>
            <h2>Phone no: +1 702-298-2442</h2>
            <h3>Email:sairrestaurant@gmail.com</h3>
        </div>
        <footer>
            <h6 class="bottom">SAIRAM.V (25012434)</h6>

        </footer>
    </body>
</html>
contanct.css
body{
    background-image: url(pexels-magda-ehlers-pexels-30018252.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    font-size: 20px;
}

a{
    padding: 15px;
    color:rgb(70, 46, 5);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: rgba(49, 42, 42, 0.768);
    position: relative;
    top: 120px;
}
.contanct-container{
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    padding: 30px;
    background-color: rgb(229, 229, 229);
    height:400px;
    width:390px;
    display: block;
    gap: 20px;
    font-size: 20px;
    position: relative;
    left: 600px;
    top:20px;
    border-radius: 10%;
}
h2,h3,h4{
    font-size: 27px;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-10-05 175222.png>)
![alt text](<Screenshot 2025-10-05 175241.png>)
![alt text](<Screenshot 2025-10-05 175259.png>)
![alt text](<Screenshot 2025-10-05 175338.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
