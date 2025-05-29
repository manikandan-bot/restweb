# Ex.06 Restaurant Website
## Date:
20/05/2025
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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tasty Kitchen</title>
    <link rel="stylesheet" href="menu.css"
    type="text/css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Tasty Kitchen</h1>
            <ul>
                <li>
                    <a href="home.html">HOME</a>
                    <a href="menu.html">MENU</a>
                    <a href="about.html">ABOUT</a>
                    <a href="administration.html">ADMINISTRATION</a>
                    <a href="contact_us.html">CONTACT</a>
                </li>
            </ul>
        </div>
    </header>
    <section id="HOME" class="home-section">
        <div class="container">
            <h2>WELCOME TO TASTY KITCHEN</h2>
            <p>"A Taste You'll Remember"</p>
            <section class="home-section1">
            <a href="menu.html" class="button">View Menu</a>
            </section>
        </div>
    </section>
   <footer>
    <div class="container">
        <p>&copy; 2025 Subash Miracle Raj.All Rights Reserved.</p>
    </div>
   </footer> 
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MENU</title>
    <link rel="stylesheet" href="menu.css"
    type="text/css">
</head>
<body>
    <header id="menu">
    <div class="container">
        <h1 id="menu2">MENU</h1>
        <ul>
            <li>
                <a href="home.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="about.html">ABOUT</a>
                <a href="administration.html">ADMINISTRATION</a>
                <a href="contact_us.html">CONTACT</a>
            </li>
        </ul>
 </div>
 </header>
 <section class="menu-section">
    <h1 id="veg">VEG-ITEMS</h1><br>
    <section class="menu-section1">
       <div>
       <img src="https://tse2.mm.bing.net/th?id=OIP.9twlNaLka1xDxL5Fmz9OFgHaHa&pid=Api&P=0&h=180" width="200" height="200">
       <h2>DOSA-75Rs</h2>
       </div>

       <div>
       <img src="https://tse3.mm.bing.net/th?id=OIP.OFbHdhFDp--X4CF3AOkTogHaE8&pid=Api&P=0&h=180" width="200" height="200">
       <h2>IDLY-30Rs</h2>
       </div>

       <div>
       <img src="https://tse2.mm.bing.net/th?id=OIP.AoxOFu3lK5TaFrw_DMJS7gHaEK&pid=Api&P=0&h=180" width="200" height="200">
       <h2>CHAPATI-60Rs</h2>
       </div>

       <div>
       <img src="https://tse1.mm.bing.net/th?id=OIP.wlr98gVZJ1JJGU8i194GFgHaFd&pid=Api&P=0&h=180" width="200" height="200">
       <h2>MEALS-100Rs</h2>
       </div>

       <div>
       <img src="https://tse4.mm.bing.net/th?id=OIP.XvrDed9Y6QyZkf4N6pqZYQHaE8&pid=Api&P=0&h=180" width="200" height="200">
       <h2>GOBI MANCHURIAN-120Rs</h2>
       </div>

       <div>
       <img src="https://tse3.mm.bing.net/th?id=OIP.qnYh1UFgIE32QkNILrBMJwHaE7&pid=Api&P=0&h=180" width="200" height="200">
       <h2>PANEER FRY-150Rs</h2>
       </div>

       <div>
        <img src="https://tse2.mm.bing.net/th?id=OIP.EQ-nUXFSSPeqnjNYaiEK6QHaIE&pid=Api&P=0&h=180" width="200" height="200">
        <h2>POORI-45Rs</h2>
       </div>
       </section>

       <h1 id="nonveg">NON-VEG ITEMS</h1><BR>
       <section class="menu-section2">
        <div>
            <img src="https://tse1.mm.bing.net/th?id=OIP.uhKx8E9C9RhzTmmnGfeWfAHaHa&pid=Api&P=0&h=180" width="200" height="200">
            <h2>CHICKEN BIRIYANI-250Rs</h2>
        </div>

        <div>
            <img src="https://tse2.mm.bing.net/th?id=OIP.pK3hTwN_FIWMmNhocPG9tgHaHa&pid=Api&P=0&h=180" width="200" height="200">
            <h2>MUTTON BIRIYANI-280Rs</h2>
        </div>

        <div>
            <img src="https://tse1.mm.bing.net/th?id=OIP.h69L8aUgJDGf_OwNsE3L0gHaE8&pid=Api&P=0&h=180" width="200" height="200">
            <h2>PRAWN 65-240Rs</h2>
        </div>

        <div>
            <img src="https://tse2.mm.bing.net/th?id=OIP.QR0pl-FVqWviiCytI0sTlAHaE8&pid=Api&P=0&h=180" width="200" height="200">
            <h2>CRAB FRY-250Rs</h2>
        </div>

        <div>
            <img src="https://tse3.mm.bing.net/th?id=OIP.KW-r9fT3IeYEg_2Wf439egHaE8&pid=Api&P=0&h=180" width="200" height="200">
            <h2>FISH FRY-220Rs</h2>
        </div>

        <div>
            <img src="https://tse4.mm.bing.net/th?id=OIP.NnXzvEnE1TGsk1z3ifMMjQHaE7&pid=Api&P=0&h=180" width="200" height="200">
            <h2>MUTTON GRAVY-280Rs</h2>
        </div>
      </section>
 </section>
 <footer>
    <div class="container">
        <p>&copy; 2025 Subash Miracle Raj.All Rights Reserved.</p>
    </div>
   </footer> 
</body>
</html

about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>MENU</title>
    <link rel="stylesheet" href="menu.css"
    type="text/css">
</head>
<body>
    <header id="about">
        <div class="container">
        <h1>ABOUT</h1>
                <ul>
                    <li>
                        <a href="home.html">HOME</a>
                        <a href="menu.html">MENU</a>
                        <a href="about.html">ABOUT</a>
                        <a href="administration.html">ADMINISTRATION</a>
                        <a href="contact_us.html">CONTACT</a>
                    </li>
                </ul>
            </div>
    </header>
    <section class="about-section">
        <p id="ABOUT1">
            Welcome to <b>tasty kitchen</b>
Our Beginnings

In the heart of <b>chennai</b>, a culinary adventure began in <b>2003</b> with the birth of <b>tasty kitchen</b>. Founded by a group of passionate food enthusiasts, our journey is a testament to the belief that every meal should be a celebration, a moment to savor and remember.
The Essence of Flavor

At <b>tasty kitchen</b>, we don’t just serve meals; we craft experiences. Headed by Executive Chef <b>miracle</b>, our kitchen is a laboratory of creativity where flavors are explored, combined, and transformed into culinary masterpieces. Each dish on our menu is a reflection of our commitment to pushing the boundaries of taste.
Our Guiding Principles
Genuine Hospitality
        </p>  
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2025 Subash Miracle Raj.All Rights Reserved.</p>
        </div>
       </footer> 
    </body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADMINISTRATION</title>
    <link rel="stylesheet" href="menu.css"
    type="text/css">
</head>
<body>
    <header id="ADMIN">
    <div class="container">
        <h1>ADMINS</h1>
        <ul>
            <li>
                <a href="home.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="about.html">ABOUT</a>
                <a href="administration.html">ADMINISTRATION</a>
                <a href="contact_us.html">CONTACT</a>
            </li>
        </ul>
 </div>
 </header>
 <section class="admin-section">
    <h1 id="chef">CHEFS</h1>
    <section class="admin-section1">
    <div>
        <img src="https://tse4.mm.bing.net/th?id=OIP.KEd7vsPiLVCUvZGwbGnY0gHaGq&pid=Api&P=0&h=180" width="200" height="200">
        <h2>GORDON RAMSAY</h2>
        <p>Executive Chef</p>
    </div>

    <div>
        <IMG SRC="http://www.michaeldeane.co.uk/resources/images/dcms/1123/Danni.jpg" width="200" height="200">
        <h2>DANNI BARRY</h2>
        <P>Head Chef</P>  
    </div>

    <div>
        <img src="https://tse4.mm.bing.net/th?id=OIP.PBKOa1jU0DMXo7GB_YgA4wHaD8&pid=Api&P=0&h=180" width="200" height="200">
        <h2>EMMA BENGTSSON</h2>
        <p>Head Chef</p>
    </div>

    <div>
        <img src="https://tse2.mm.bing.net/th?id=OIP.a4gVeRbp5AIYda1edHAVugHaE8&pid=Api&P=0&h=180" width="200" height="200">
        <h2>ERIC PRAS</h2>
        <p>Sous Chef</p>
    </div>

    <div>
        <img src="https://tse2.mm.bing.net/th?id=OIP.CVic2VHx6sNHvuU9GKbvtgHaGm&pid=Api&P=0&h=180" width="200" height="200">
        <h2>JOAN ROCA</h2>
        <p>Sous Chef</p>
    </div>

    <div>
        <img src="https://tse2.mm.bing.net/th?id=OIP.qTUNQguXkhSyhND4vAfsbAHaEF&pid=Api&P=0&h=180" width="200" height="200">
        <h2>NADIA SANTINI</h2>
        <p>Sous Chef</p>
    </div>
    </section>
 </section>
 <footer>
    <div class="container">
        <p>&copy; 2025 Subash Miracle Raj.All Rights Reserved.</p>
    </div>
   </footer> 
</body>
</html>

contact_us.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>CONTACT</title>
    <link rel="stylesheet" href="menu.css"
    type="text/css">
</head>
<body>
    <header id="CONTACT">
        <div class="container">
        <h1>CONTACT</h1>
                <ul>
                    <li>
                        <a href="home.html">HOME</a>
                        <a href="menu.html">MENU</a>
                        <a href="about.html">ABOUT</a>
                        <a href="administration.html">ADMINISTRATION</a>
                        <a href="contact_us.html">CONTACT</a>
                    </li>
                </ul>
            </div>
    </header>
    <section class="contact-section">
    <h2>
        <address>
            135B, Srp colony 1st Main Road, Next to Mughil Soup, Peravallur,
            kolathur,Chennai,Tamil Nadu 600082<br>
            phone: 8072867569<br>
            Email:tastykitchenadmin@gmail.com
       </address>
    </h2>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2025 Subash Miracle Raj.All Rights Reserved.</p>
        </div>
       </footer> 
    </body>
    </html>

    menu.css

    .container{
    width: 80%;
    margin: 0 auto;
}
body{
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}
header{
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}
header h1{
    font-size: 50px;
    text-align: center;
}
.home-section{
    background-image: url('sample_0.jpg');
    background-size: cover;
    background-position: center;
    align-items: center;
    text-align: center;
    color: #fff;
    height: 100vh;
    justify-content: center;
    display: flex;
}
.home-section h2{
    font-size: 3rem;
    text-align: center;
    align-items: center;
}
.home-section p{
    font-size: 1.2rem;
    margin: 1em 0;
    text-align: center;
    align-items: center;
}
ul{
    list-style: none;
    text-align: center;
    word-spacing: 2em;
}
ul li a{
    color: #fff;
    text-decoration: none;
}
h2{
    align-items: center;
    text-align: center;
}
p{
    align-items: center;
    text-align: center;
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Georgia, 'Times New Roman', Times, serif;
}

#about{
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
    align-items: center;
}
.about-section{
    background-image: url('sample_0.jpg');
    background-size: cover;
    background-position: center;
    align-items: center;
    text-align: justify;
    color: #fff;
    font-size: 25px;
    height: 100vh;
    word-spacing: 0.7em;
    padding: 50px;
}
#contact{
    background-color: #333;
    color: #fff;
    align-items: center;
    text-align: center;
    padding: 1em 0;
}
.contact-section{
    background-image: url('sample_0.jpg');
    background-position: center;
    background-size: cover;
    text-align: center;
    align-items: center;
    color: #fff;
    height: 100vh;
    font-size: 20px;
    font-family: cursive;
    word-spacing: 0.7em;
    padding: 50px;
}
#menu{
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
    align-items: center;
}
.menu-section{
    background-image: url('sample_0.jpg');
    background-position: center;
    background-size: cover;
    color: #fff;
    size: 20px;
    padding: 40px;
    align-items: center;
    text-align: center;
}
.menu-section1{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}
.menu-section1 div{
    margin: 30px;
    align-items: center;
    text-align: center;
}
.menu-section2{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}
.menu-section2 div{
    margin: 30px;
    align-items: center;
    text-align: center;
}
#veg{
    text-decoration: underline;
    font-style: bold;
    font-size: 40px;
    background-color: #ff6347;
}
#nonveg{
    text-decoration: underline;
    font-size: 40px;
    font-style: bold;
    background-color: #ff6347;
}
.admin-section{
    background-image: url('sample_0.jpg');
    background-position: center;
    background-size: cover;
    height: 100vh;
    color: #fff;
    size: 20px;
    padding: 40px;
    align-items: center;
    text-align: center;
}
.admin-section1{
    display: flex;
    align-items: center;
    text-align: center;
    flex-wrap: wrap;
}
.admin-section div{
    text-align: center;
    align-items: center;
    margin: 30px;
}
#chef{
    font-size: bold;
    text-decoration: underline;
    font-size: 40px;
}
footer{
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em o;
}
.button{
    background-color: #ff6347;
    color: #fff;
    padding: 1em 2em;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-05-29 091634.png>) 
![alt text](<Screenshot 2025-05-29 091659.png>) 
![alt text](<Screenshot 2025-05-29 091717.png>) 
![alt text](<Screenshot 2025-05-29 091732.png>) 
![alt text](<Screenshot 2025-05-29 091743.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
