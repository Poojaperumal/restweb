# Ex.07 Restaurant Website
## Date:14/12/2024

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
    <title> VIGNESH </title>
  <head>
      <style>
body{
  display: flex;
  justify-content: center;
  flex-direction: column;
}
h1{
  background-color: orange;
  border: 2px solid black;
  border-radius: 10px;
}
.home{
  border: 2px solid black;
  height: 10%;
  border-radius: 20px;
  display: flex;
  justify-content: space-evenly;
  background-color: black  ;
}
a{
  border: 2px solid black;
  width: 10%;
  align-items: center;
  border-radius: 20px;
  background-color: orange;
}
.vijay{
  border: 2px solid black;
  height: 78%;
  border-radius: 20px;
  background-image: url('temp.png');
  background-size: cover;
}
h3{
  position: relative;
  bottom: 70px;
  left: 40%;
  color: aliceblue;
  background-color: black;
  width: 20%;
  border-radius: 20px;
}
      </style>
  </head>
  <body>
      <h1 align="center"> VIGNESH</h1>
      <div class="home">
          <a align="center" href="rest.html">HOME</a>
          <a align="center" href="menu.html">MENU</a>
          <a align="center" href="admin.html">ADMINISTRATION</a>
          <a align="center" href="cont.html">CONTACT</a>
      </div>
      <div class="vijay"></div>
      <h3 align="center">Designed and Developed by POOJA</h3>
      
  </body>
</html>

  menu.html

<html>
    <title>Menu</title>
    <head>
        <style>
.main{
    width: 99%;
    height: 99%;
    background-color: bisque;
    justify-content: center;
    border: 2px solid black;
    border-radius: 20px;
    
}
.main h1{
    width: 500px;
    position: relative;
    top: 1px;
    left: 480px;
    border: 1px;
    border-radius: 100px;
    padding: 5px;
    background-color: black;
    color:rgb(230, 234, 238);
    
    font-family: 'Times New Roman', Times, serif;
    font-size:  50px;
}

.h1{
    display: flex;
    justify-content: space-around;
    position: relative;
    left: 35px;
    width: 95%;
    height: 90%;
}
.h2{
    display: flex;
    justify-content: space-around;
    position: relative;
    left: 35px;
    bottom: 400px;
    width: 95%;
    height: 90%;
}
.i1{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("th.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i2{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("chic.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i3{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("egg.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i4{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("curd.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i5{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("dos.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i6{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("idly.webp");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i7{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("biri.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i8{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("pan.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i9{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("fish.jpg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i10{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("chap.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i11{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("poro.webp");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
.i12{
    width: 20%;
    height: 40%;
    color: rgb(217, 223, 230,217);
    background-image: url("poori.jpeg");
    background-size: cover;
    background-color: darkblue;
    border: 1px solid darkblue;
    border-radius: 50px;
}
h2{
    color: aliceblue;
    position: relative;
    left: 30px;
    border: 1px solid rgb(12, 12, 20);
    background-color: rgb(10, 10, 13);
    width: 80%;
    height: 8%;
    border-radius: 80px;
}
        </style>
    </head>
    <body>
        <div class="main">
            <h1 align="center">MENU</h1>
            
                <div class="h1">
                    <div class="i1">
                        <h2 align="center">TOMATO RICE</h2>

                    </div>
                    <div class="i2">
                        <h2 align="center">CHICKEN RICE</h2>

                    </div>
                    <div class="i3">
                        <h2 align="center">EGG RICE</h2>

                    </div>
                    <div class="i4">
                        <h2 align="center">CURD RICE</h2>

                    </div>
                    <div class="i5">
                        <h2 align="center">DOSA</h2>

                    </div>
                    <div class="i6">
                        <h2 align="center">IDLY</h2>

                    </div>
                </div>
                <div class="h2">
                    <div class="i7">
                        <h2 align="center">BIRIYANI</h2>

                    </div>
                    <div class="i8">
                        <h2 align="center">PANEER</h2>

                    </div>
                    <div class="i9">
                        <h2 align="center">FISH SAUCE</h2>

                    </div>
                    <div class="i10">
                        <h2 align="center">CHAPPTI</h2>

                    </div>
                    <div class="i11">
                        <h2 align="center">PAROTTA</h2>

                    </div>
                    <div class="i12">
                        <h2 align="center">POORI</h2>

                    </div>
                </div>
            
        </div>
    </body>
</html>

   admin .html

   <!DOCTYPE html>
   <html lang="en">
   <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>

    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            
            background-color: #f63a3a;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #27cbbe;
            color: rgb(69, 171, 199);
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(1, 33, 15, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: rgb(33, 121, 176);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #2a688b;
        }

        .admin-container {
            padding: 40px 20px;
            background: #743793;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2.5rem;
            color: #315b67;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .admin-item {
            background: rgb(180, 185, 153);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(159, 154, 149, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        footer {
            background: #978b5a;
            color: rgb(123, 154, 169);
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #dba419;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>    
<div class="admin-container">
        <h1>OUR BACKBONES</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="rehman.jpeg" alt="CEO">
                <div class="admin-details">
                    <h3>Rehman</h3>
                    <p>CEO of THE VIGNESH</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="suresh.jpg" alt="Manager">
                <div class="admin-details">
                    <h3>Suresh</h3>
                    <p>Manager of THE VIGNESH </p>
                </div>
            </div>

            <div class="admin-item">
                <img src="sriram.jpg" alt="Master Chef">
                <div class="admin-details">
                    <h3>Sriram</h3>
                    <p>Master Chef of THE VIGNESH</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="saravanan.png" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>Saravanan</h3>
                    <p>Assistant Managing Director of THE VIGNESH</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
         <a href="res.html">Back to Home</a></p>
    </footer>

</body>
</html>

   cont.html

    <html>
    <head>
        <title> CONTACT </title>
    <style>
        
        body{
        
            
            background-size: cover;
            background-position: center;
        }
        body{
            display: inline blocks;
            margin:0 600px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 23px;
            font-weight: bolder;
            background-color: black;
            position:absolute;
            top: 200px;
        }
    </style>
    </head>
    <body>
    <div class="nav-list">
        </div>
    <center>
        <section id="contact">  
            <h1 style="color:rgb(220, 233, 240)">CONTACT<h1>
            <h4  style="color:rgb(217, 237, 240)">7438291456 <br> vignesh@gmail.com</h4>
            <P  style="color:rgb(227, 235, 244)">Address: Anna nagar street, <br>Thiruppathur main road,<br>Thiruppathur <br>
            </P>
         </section> 
    </center>
   </body>
</html>

```


## OUTPUT:
![alt text](<Screenshot (8).png>) 
![alt text](<Screenshot (9).png>)
![alt text](<Screenshot (10).png>) 
![alt text](<Screenshot (11).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
