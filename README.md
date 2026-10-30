# EXPERIMENT 2 : COMMERCIAL WEBSITE USING FLEXBOX
## NAME : RUSHMITHA  R
## REGISTRATION NUMBER : 212224040281 

## DATE: 30/10/2026

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

## PROGRAM :
exp2.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clover & Cream | Coffee House</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Header -->
    <header>
        <div class="logo">
            CLOVER <span>&</span> CREAM
            <small>COFFEE HOUSE</small>
        </div>

        <nav>
            <a href="#home">Home</a>
            <a href="#menu">Our Menu</a>
            <a href="#special">Specials</a>
            <a href="#story">Our Story</a>
            <a href="#contact">Contact</a>
        </nav>

        <a href="#menu" class="nav-button">Explore Menu</a>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">

        <div class="hero-content">
            <p class="eyebrow">YOUR NEW FAVOURITE COFFEE SPOT</p>

            <h1>A little sip of <span>happiness.</span></h1>

            <p class="hero-text">
                Freshly brewed coffee, delicious treats and
                beautiful moments. Your perfect little escape
                starts here.
            </p>

            <a href="#menu" class="main-button">Discover Our Menu →</a>

            <p class="hero-note">♡ Made with love, served with warmth.</p>
        </div>

        <div class="hero-image">
            <img src="https://images.unsplash.com/photo-1442512595331-e89e73853f31?w=900"
                 alt="Freshly brewed coffee">
        </div>

    </section>

    <!-- Categories -->
    <section class="categories">

        <div class="category">
            <span>☕</span>
            <h3>Fresh Coffee</h3>
            <p>Made fresh every day</p>
        </div>

        <div class="category">
            <span>🥐</span>
            <h3>Fresh Bakery</h3>
            <p>Delicious little treats</p>
        </div>

        <div class="category">
            <span>♡</span>
            <h3>Cozy Moments</h3>
            <p>Made for your happy hours</p>
        </div>

        <div class="category">
            <span>🌿</span>
            <h3>Quality Beans</h3>
            <p>Carefully selected blends</p>
        </div>

    </section>

    <!-- Menu Section -->
    <section class="menu" id="menu">

        <div class="section-heading">
            <p class="eyebrow">A LITTLE SOMETHING FOR EVERYONE</p>
            <h2>Made to make you smile.</h2>
            <p>Explore our freshly prepared favourites.</p>
        </div>

        <div class="menu-container">

            <div class="menu-card">
                <img src="https://images.unsplash.com/photo-1510707577719-ae7c14805e3a?w=600"
                     alt="Espresso coffee">

                <div class="card-info">
                    <span>COFFEE CLASSICS</span>
                    <h3>Classic Espresso</h3>
                    <p>Rich, bold and beautifully simple.</p>
                    <div class="price">₹120</div>
                </div>
            </div>

            <div class="menu-card">
                <img src="https://images.unsplash.com/photo-1534778101976-62847782c213?w=600"
                     alt="Cappuccino">

                <div class="card-info">
                    <span>HOUSE FAVOURITE</span>
                    <h3>Velvet Cappuccino</h3>
                    <p>Silky milk foam with a coffee kick.</p>
                    <div class="price">₹160</div>
                </div>
            </div>

            <div class="menu-card">
                <img src="https://images.unsplash.com/photo-1461023058943-07fcbe16d735?w=600"
                     alt="Iced latte">

                <div class="card-info">
                    <span>COOL & REFRESHING</span>
                    <h3>Iced Vanilla Latte</h3>
                    <p>Chilled coffee with a sweet twist.</p>
                    <div class="price">₹180</div>
                </div>
            </div>

            <div class="menu-card">
                <img src="https://images.unsplash.com/photo-1570968915860-54d5c301fa9f?w=600"
                     alt="Mocha coffee">

                <div class="card-info">
                    <span>SWEET INDULGENCE</span>
                    <h3>Chocolate Mocha</h3>
                    <p>A lovely blend of coffee and chocolate.</p>
                    <div class="price">₹190</div>
                </div>
            </div>

        </div>

    </section>

    <!-- Special Offer -->
    <section class="special" id="special">

        <div class="special-image">
            <img src="https://images.unsplash.com/photo-1555507036-ab1f4038808a?w=800"
                 alt="Freshly baked croissant">
        </div>

        <div class="special-content">
            <p class="eyebrow">A LITTLE EXTRA LOVE</p>
            <h2>Your coffee deserves a little treat.</h2>

            <p>
                Pair your favourite coffee with our freshly
                baked bakery treats. Because good coffee
                deserves good company!
            </p>

            <h3>COFFEE + CROISSANT COMBO</h3>
            <h2 class="offer-price">₹199 <span>Only!</span></h2>

            <a href="#contact" class="main-button">Visit Us Today →</a>
        </div>

    </section>

    <!-- About Section -->
    <section class="story" id="story">

        <div class="story-content">
            <p class="eyebrow">A STORY BREWED WITH LOVE</p>

            <h2>More than coffee. It's a feeling.</h2>

            <p>
                At Clover & Cream, we believe the little things
                make life beautiful. From the aroma of freshly
                ground coffee to the first sip of your favourite
                latte, every moment matters.
            </p>

            <p>
                Our café is a place to relax, connect, work
                and create memories. We bring together quality
                ingredients, warm hospitality and a love for
                everything coffee.
            </p>

            <a href="#contact" class="text-link">Come say hello →</a>
        </div>

        <div class="story-image">
            <img src="https://images.unsplash.com/photo-1445116572660-236099ec97a0?w=800"
                 alt="Cozy coffee shop interior">
        </div>

    </section>

    <!-- Quote Section -->
    <section class="quote">
        <p>“Life is better with a little coffee and a lot of love.”</p>
        <span>— CLOVER & CREAM</span>
    </section>

    <!-- Contact Section -->
    

    <!-- Footer -->
    <footer>

        <div class="footer-logo">
            CLOVER <span>&</span> CREAM
            <p>GOOD COFFEE. SWEET MOMENTS.</p>
        </div>

        <div class="footer-links">
            <a href="#home">Home</a>
            <a href="#menu">Menu</a>
            <a href="#story">About</a>
            <a href="#contact">Contact</a>
        </div>

        <div class="social-links">
            <a href="https://www.instagram.com/">Instagram</a>
            <a href="https://www.facebook.com/">Facebook</a>
            <a href="https://www.pinterest.com/">Pinterest</a>
        </div>

        <p class="copyright">
            © 2026 Clover & Cream. All Rights Reserved.
        </p>

    </footer>

</body>
</html>
```
style.css

```
/* GLOBAL STYLES */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-color: #faf7f1;
    color: #3d3029;
    line-height: 1.6;
}

/* HEADER */
header {
    background-color: #faf7f1;
    padding: 22px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    border-bottom: 1px solid #e8ded2;
}

.logo {
    font-size: 23px;
    font-weight: bold;
    letter-spacing: 2px;
    color: #573c2d;
}

.logo span {
    color: #b68b68;
}

.logo small {
    display: block;
    font-size: 9px;
    text-align: center;
    letter-spacing: 4px;
}

nav {
    display: flex;
    gap: 27px;
    flex-wrap: wrap;
}

nav a {
    text-decoration: none;
    color: #57483e;
    font-size: 14px;
    transition: 0.3s;
}

nav a:hover {
    color: #b17b52;
}

.nav-button {
    background-color: #6b4b3b;
    color: white;
    padding: 11px 20px;
    text-decoration: none;
    border-radius: 30px;
    font-size: 13px;
    transition: 0.3s;
}

.nav-button:hover {
    background-color: #a67c59;
}

/* HERO SECTION */
.hero {
    padding: 75px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 50px;
    min-height: 570px;
}

.hero-content {
    flex: 1;
}

.eyebrow {
    color: #a77b58;
    font-size: 11px;
    font-weight: bold;
    letter-spacing: 3px;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: 65px;
    line-height: 1.15;
    color: #49362b;
    margin-bottom: 22px;
}

.hero h1 span {
    color: #b17b52;
    font-style: italic;
}

.hero-text {
    color: #827166;
    font-size: 17px;
    max-width: 430px;
    margin-bottom: 30px;
}

.main-button {
    display: inline-block;
    background-color: #6b4b3b;
    color: white;
    padding: 14px 25px;
    border-radius: 30px;
    text-decoration: none;
    transition: 0.3s;
}

.main-button:hover {
    background-color: #b17b52;
    transform: translateY(-3px);
}

.hero-note {
    margin-top: 25px;
    color: #a17f69;
    font-size: 13px;
}

.hero-image {
    flex: 1;
}

.hero-image img {
    width: 100%;
    height: 420px;
    object-fit: cover;
    border-radius: 180px 180px 15px 15px;
    box-shadow: 15px 15px 0px #e9dfd1;
}

/* CATEGORY SECTION */
.categories {
    background-color: #eee7dc;
    padding: 35px 7%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    gap: 25px;
    flex-wrap: wrap;
    text-align: center;
}

.category {
    flex: 1;
    min-width: 150px;
}

.category span {
    font-size: 30px;
}

.category h3 {
    font-size: 16px;
    margin: 8px 0;
}

.category p {
    color: #8c796b;
    font-size: 13px;
}

/* MENU SECTION */
.menu {
    padding: 80px 7%;
}

.section-heading {
    text-align: center;
    margin-bottom: 45px;
}

.section-heading h2 {
    font-size: 38px;
    color: #49362b;
    margin-bottom: 10px;
}

.section-heading > p:last-child {
    color: #8c796b;
}

/* FLEXBOX MENU */
.menu-container {
    display: flex;
    justify-content: center;
    align-items: stretch;
    gap: 25px;
    flex-wrap: wrap;
}

.menu-card {
    background-color: white;
    width: 250px;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 5px 20px rgba(70, 50, 35, 0.08);
    transition: transform 0.3s, box-shadow 0.3s;
}

.menu-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 12px 25px rgba(70, 50, 35, 0.15);
}

.menu-card img {
    width: 100%;
    height: 210px;
    object-fit: cover;
}

.card-info {
    padding: 20px;
}

.card-info span {
    font-size: 10px;
    color: #a77b58;
    letter-spacing: 1.5px;
    font-weight: bold;
}

.card-info h3 {
    margin: 10px 0;
    font-size: 20px;
}

.card-info p {
    color: #8c796b;
    font-size: 13px;
}

.price {
    color: #a16b43;
    font-size: 21px;
    font-weight: bold;
    margin-top: 15px;
}

/* SPECIAL OFFER */
.special {
    background-color: #eae0d3;
    padding: 65px 9%;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 65px;
    flex-wrap: wrap;
}

.special-image {
    flex: 1;
    min-width: 260px;
}

.special-image img {
    width: 100%;
    height: 350px;
    object-fit: cover;
    border-radius: 12px;
}

.special-content {
    flex: 1;
    min-width: 260px;
}

.special-content h2 {
    font-size: 39px;
    line-height: 1.3;
    margin-bottom: 18px;
}

.special-content p {
    color: #806d5f;
    margin-bottom: 20px;
}

.special-content h3 {
    font-size: 13px;
    letter-spacing: 2px;
    margin-top: 25px;
}

.special-content .offer-price {
    color: #a16b43;
    font-size: 35px;
    margin: 10px 0 20px;
}

.offer-price span {
    font-size: 18px;
}

/* STORY SECTION */
.story {
    padding: 85px 9%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 60px;
    flex-wrap: wrap;
}

.story-content {
    flex: 1;
    min-width: 260px;
}

.story-content h2 {
    font-size: 40px;
    line-height: 1.3;
    margin-bottom: 20px;
}

.story-content p {
    color: #806d5f;
    margin-bottom: 18px;
}

.text-link {
    display: inline-block;
    color: #a16b43;
    text-decoration: none;
    font-weight: bold;
    margin-top: 10px;
}

.text-link:hover {
    color: #49362b;
}

.story-image {
    flex: 1;
    min-width: 260px;
}

.story-image img {
    width: 100%;
    height: 370px;
    object-fit: cover;
    border-radius: 12px;
}

/* QUOTE SECTION */
.quote {
    background-color: #594235;
    color: #f8eee2;
    padding: 65px 20px;
    text-align: center;
}

.quote p {
    font-size: 28px;
    font-style: italic;
    margin-bottom: 15px;
}

.quote span {
    font-size: 11px;
    letter-spacing: 3px;
    color: #d5b99d;
}

/* CONTACT SECTION */
.contact {
    padding: 75px 9%;
    background-color: #f2ece3;
}

.contact-container {
    display: flex;
    justify-content: space-between;
    gap: 50px;
    flex-wrap: wrap;
}

.contact-info,
.contact-form {
    flex: 1;
    min-width: 260px;
}

.contact-info h3,
.contact-form h3 {
    font-size: 23px;
    margin-bottom: 25px;
}

.contact-info p {
    margin: 18px 0;
    color: #806d5f;
}

.contact-form form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 14px;
    border: 1px solid #d9c9b8;
    border-radius: 6px;
    background-color: #faf7f1;
    font-family: Arial, sans-serif;
    outline: none;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: #a77b58;
}

.contact-form textarea {
    height: 110px;
    resize: vertical;
}

.contact-form button {
    background-color: #6b4b3b;
    color: white;
    padding: 14px;
    border: none;
    border-radius: 30px;
    cursor: pointer;
    font-size: 15px;
    transition: 0.3s;
}

.contact-form button:hover {
    background-color: #a77b58;
}

/* FOOTER */
footer {
    background-color: #34261f;
    color: #f8eee2;
    text-align: center;
    padding: 40px 20px 20px;
}

.footer-logo {
    font-size: 25px;
    font-weight: bold;
    letter-spacing: 3px;
    color: #e2bd99;
}

.footer-logo span {
    color: white;
}

.footer-logo p {
    font-size: 10px;
    letter-spacing: 3px;
    margin-top: 8px;
}

.footer-links,
.social-links {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
    margin: 25px 0;
}

.footer-links a,
.social-links a {
    text-decoration: none;
    color: #e8d6c4;
    font-size: 13px;
    transition: 0.3s;
}

.footer-links a:hover,
.social-links a:hover {
    color: #d3a47c;
}

.copyright {
    border-top: 1px solid #675448;
    padding-top: 20px;
    margin-top: 25px;
    color: #c4b2a3;
    font-size: 12px;
}

/* RESPONSIVE DESIGN */
@media (max-width: 768px) {

    header {
        flex-direction: column;
        gap: 20px;
    }

    nav {
        justify-content: center;
        gap: 15px;
    }

    .hero {
        flex-direction: column;
        text-align: center;
        padding: 50px 7%;
    }

    .hero h1 {
        font-size: 43px;
    }

    .hero-text {
        margin-left: auto;
        margin-right: auto;
    }

    .hero-image img {
        height: 300px;
        border-radius: 100px 100px 12px 12px;
    }

    .section-heading h2 {
        font-size: 30px;
    }

    .menu-container {
        flex-direction: column;
        align-items: center;
    }

    .menu-card {
        width: 100%;
        max-width: 350px;
    }

    .special,
    .story {
        flex-direction: column;
    }

    .special-content h2,
    .story-content h2 {
        font-size: 31px;
    }

    .quote p {
        font-size: 22px;
    }
}
```



## OUTPUT :


![alt text](<Screenshot 2026-10-30 110455.png>)

![alt text](<Screenshot 2026-10-30 110510.png>)


![alt text](<Screenshot 2026-10-30 110524.png>)


![alt text](<Screenshot 2026-10-30 110718.png>)

![alt text](<Screenshot 2026-10-30 110901.png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
