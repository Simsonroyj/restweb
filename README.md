# Ex.06 Restaurant Website
## Date:20.12.2025

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
index.html

<!DOCTYPE html>
<html>
<head>
<title>The Flavor Fusion | Welcome</title>

<style>
body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    background-image: url('https://images.unsplash.com/photo-1414235077428-338989a2e8c0');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    color: white;
}

/* Overlay */
.overlay{
    background: rgba(0,0,0,0.6);
    min-height: 100vh;
}

/* Navbar */
.navbar{
    background: white;
    padding: 15px;
    text-align: right;
}
.navbar a{
    margin: 15px;
    text-decoration: none;
    color: purple;
    font-weight: bold;
    transition: 0.3s;
}
.navbar a:hover{
    color: #d4a017;
}

/* Hero Section */
.hero{
    text-align: center;
    padding-top: 120px;
}

.hero h1{
    font-size: 70px;
    color: #f5c542;
    margin-bottom: 10px;
    letter-spacing: 2px;
}

.hero h3{
    font-weight: normal;
    font-size: 24px;
    margin-bottom: 30px;
    font-style: italic;
}

.hero p{
    max-width: 700px;
    margin: auto;
    font-size: 18px;
    line-height: 1.6;
}

/* Buttons */
.buttons{
    margin-top: 40px;
}

.buttons a{
    display: inline-block;
    padding: 15px 35px;
    margin: 15px;
    border-radius: 30px;
    text-decoration: none;
    font-size: 18px;
    transition: 0.3s;
}

.btn-primary{
    background: #f5c542;
    color: black;
}

.btn-primary:hover{
    background: white;
}

.btn-outline{
    border: 2px solid white;
    color: white;
}

.btn-outline:hover{
    background: white;
    color: black;
}

/* Footer */
.footer{
    position: absolute;
    bottom: 0;
    width: 100%;
    background: black;
    text-align: center;
    padding: 10px;
    font-size: 14px;
}
</style>
</head>

<body>

<div class="overlay">

    <!-- NAVBAR -->
    <div class="navbar">
        <a href="index.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <!-- HERO -->
    <div class="hero">
        <h1>THE FAMOUS RESTAURANT</h1>
        <h3>A Golden Taste of India</h3>

        <p>
            Experience the perfect blend of tradition and taste.
            At THE FAMOUS RESTAURANT, we bring you rich flavors, fresh ingredients,
            and a warm ambiance that turns every meal into a memorable moment.
        </p>

        <div class="buttons">
            <a href="menu.html" class="btn-primary">View Menu</a>
            <a href="contact.html" class="btn-outline">Contact Us</a>
        </div>
    </div>

    <!-- FOOTER -->
    <div class="footer">
        © SIMSONROY.J (25009397)
    </div>

</div>

</body>
</html>

menu.html

<!DOCTYPE html>
<html>
<head>
<title>Menu</title>
<style>
body{
    margin:0;
    font-family:Arial;
    background-image:url('https://images.unsplash.com/photo-1504674900247-0877df9cc836');
    background-size:cover;
    background-attachment:fixed;
}

/* Navbar */
.navbar{
    background:white;
    padding:15px;
    text-align:right;
}
.navbar a{
    margin:15px;
    text-decoration:none;
    color:purple;
    font-weight:bold;
}

h1{
    text-align:center;
    color:white;
    letter-spacing:3px;
}

.menu-container{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    padding:30px;
}

.card{
    background:white;
    width:220px;
    margin:15px;
    border-radius:15px;
    text-align:center;
    box-shadow:0 4px 8px rgba(0,0,0,0.6);
}

.card img{
    width:100%;
    height:160px;
    border-radius:15px 15px 0 0;
}

.card h3{margin:10px 0;}
.card p{font-weight:bold;margin-bottom:15px;}
</style>
</head>
<body>

<div class="navbar">
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
</div>

<h1>MENU</h1>

<div class="menu-container">

<div class="card">
<img src="https://tse2.mm.bing.net/th/id/OIP.d6D1xlOV43cAc34NXdTcFQHaJu?cb=ucfimg2&ucfimg=1&rs=1&pid=ImgDetMain&o=7&rm=3">
<h3>Dosa</h3><p>Rs.50</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1631515243349-e0cb75fb8d3a">
<h3>Biryani</h3><p>Rs.250</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93">
<h3>Tea</h3><p>Rs.15</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1589302168068-964664d93dc0">
<h3>Noodles</h3><p>Rs.350</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1601050690597-df0568f70950">
<h3>Veg Lunch</h3><p>Rs.450</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1511920170033-f8396924c348">
<h3>Coffee</h3><p>Rs.20</p>
</div>

</div>
</body>
</html>

admin.html

<!DOCTYPE html>
<html>
<head>
<title>Admin - Famous Restaurant</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background-image: url('https://images.unsplash.com/photo-1507679799987-c73779587ccf');
    background-size: cover;
    background-attachment: fixed;
}

/* Navbar */
.navbar{
    background: white;
    padding: 15px;
    text-align: right;
}
.navbar a{
    margin: 15px;
    text-decoration: none;
    color: purple;
    font-weight: bold;
}

/* Admin container */
.admin-container{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 50px;
}

/* Card */
.card{
    background: #f4c20d;
    width: 200px;
    height: 380px;
    margin: 15px;
    border-radius: 20px;
    text-align: center;
    padding-top: 20px;
}

/* Image */
.card img{
    width: 130px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
}

/* Name */
.card h3{
    margin: 15px 0 5px;
    font-size: 16px;
}

/* Role box */
.role{
    background: white;
    margin: 15px;
    padding: 8px;
    border-radius: 5px;
    font-weight: bold;
}

/* Phone */
.card p{
    font-size: 14px;
    margin-top: 10px;
}
</style>
</head>

<body>

<!-- NAVBAR -->
<div class="navbar">
    <a href="index.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
</div>

<!-- ADMIN CARDS -->
<div class="admin-container">

    <div class="card">
        <img src="https://randomuser.me/api/portraits/men/32.jpg">
        <h3>VIJAY</h3>
        <div class="role">Manager</div>
        <p>📞 9856423177</p>
    </div>

    <div class="card">
        <img src="https://randomuser.me/api/portraits/men/45.jpg">
        <h3>SURIYA</h3>
        <div class="role">Chef</div>
        <p>📞 9654782317</p>
    </div>

    <div class="card">
        <img src="https://randomuser.me/api/portraits/men/65.jpg">
        <h3>AJITH</h3>
        <div class="role">Assistant Chef</div>
        <p>📞 9758462311</p>
    </div>

    <div class="card">
        <img src="https://randomuser.me/api/portraits/women/44.jpg">
        <h3>MADONA</h3>
        <div class="role">Cashier</div>
        <p>📞 9458761223</p>
    </div>

    <div class="card">
        <img src="https://randomuser.me/api/portraits/women/52.jpg">
        <h3>TAMANA</h3>
        <div class="role">Waiter</div>
        <p>📞 8974562734</p>
    </div>

    <div class="card">
        <img src="https://randomuser.me/api/portraits/men/78.jpg">
        <h3>RAJINI</h3>
        <div class="role">Cleaner</div>
        <p>📞 9856471237</p>
    </div>

</div>

</body>
</html>

contact.html

<!DOCTYPE html>
<html>
<head>
<title>Contact Us | The Flavor Fusion</title>

<style>
body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    background-image: url('https://images.unsplash.com/photo-1502920514313-52581002a659');
    background-size: cover;
    background-attachment: fixed;
    color: white;
}

/* Overlay */
.overlay{
    background: rgba(0,0,0,0.65);
    min-height: 100vh;
}

/* Navbar */
.navbar{
    background: white;
    padding: 15px;
    text-align: right;
}
.navbar a{
    margin: 15px;
    text-decoration: none;
    color: purple;
    font-weight: bold;
    transition: 0.3s;
}
.navbar a:hover{
    color: #d4a017;
}

/* Contact Section */
.contact-container{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 80px 20px;
}

.contact-card{
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(10px);
    padding: 50px;
    width: 420px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 10px 25px rgba(0,0,0,0.5);
}

.contact-card h1{
    color: #f5c542;
    margin-bottom: 25px;
    font-size: 40px;
}

.info{
    font-size: 18px;
    margin: 20px 0;
    letter-spacing: 0.5px;
}

.icon{
    font-size: 22px;
    margin-right: 8px;
}

/* Footer */
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background: black;
    text-align: center;
    padding: 8px;
    font-size: 14px;
}
</style>
</head>

<body>

<div class="overlay">

    <!-- NAVBAR -->
    <div class="navbar">
        <a href="index.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <!-- CONTACT -->
    <div class="contact-container">
        <div class="contact-card">
            <h1>Contact Us</h1>

            <div class="info">
                <span class="icon">📍</span>
                123 Main Road, Chennai, Tamil Nadu
            </div>

            <div class="info">
                <span class="icon">📞</span>
                +91 98765 43210
            </div>

            <div class="info">
                <span class="icon">📧</span>
                thefamousresturant@gmail.com
            </div>

            <div class="info">
                <span class="icon">⏰</span>
                Open Daily: 9:00 AM – 11:00 PM
            </div>
        </div>
    </div>

    <!-- FOOTER -->
    <div class="footer">
        © SIMSONROY.J (25017613)
    </div>

</div>

</body>
</html>
```

## OUTPUT:

<img width="1920" height="1080" alt="Screenshot 2025-12-20 160046" src="https://github.com/user-attachments/assets/9e58af02-d5a6-4538-8bad-9c2823bd06bf" />

<img width="1920" height="1080" alt="Screenshot 2025-12-20 160104" src="https://github.com/user-attachments/assets/dac7de53-3d96-4166-8ecc-068eddfd5888" />

<img width="1920" height="1080" alt="Screenshot 2025-12-20 160119" src="https://github.com/user-attachments/assets/c31e2f8d-a09a-47f0-b34e-98241f18a243" />

<img width="1920" height="1080" alt="Screenshot 2025-12-20 160133" src="https://github.com/user-attachments/assets/5194b38d-9f02-4c08-9901-39b0d4ef4768" />

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
