# Ex.07 Software Product Company Website
## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:purple;
        font-family:'Gill sans MT';
        font-size: 30px;
        text-align:center;
    }
    img{
        
        height:200px;
        width:200;
        position:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: teal; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color:teal; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:teal; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:teal; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>YUVA SOFTWARE DEVELOPING CENTER</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Make your future bright by developing your skills. </b></marquee>
                    <p style="color:orange; font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our Teaching center.</p>
                    </div>
                    
                    <div class="content1">Software developers are the creative force behind computer programs of all kinds.<br>They design and write the code used to build everything from operating systems to apps to video games.<br>A Software Developer designs and builds computer programs that power mobile devices, desktop computers, and even cars.<br>Software developers need to stay up-to-date on the latest advancements regarding the tools, frameworks, programming languages, and apps to achieve success.<br>You can learn from<span style="background-color:lime">YUVA SOFTWARE DEVELOPING CENTER</span>
                         for Rs.1000 | Get free certificate | Intenship programs | Workshops | Hackathons | And much more...
                        <img src="/static/images/home.png"></div>
                    
                    <br>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by Yuvaranithulasingam</footer></div>
            </div>
        </div>
    </body>
</html>

products.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 1260px;
            width: 70%;
            border: 12px solid lawngreen;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
            color:blueviolet;
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid darkblue;
            background-color: white;
            width:90%;
            height:900px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(/static/images/python.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
        }
        .l1{
            color: crimson;
            position:relative;
            right:320px;
            
            
        }
        .ph2{
            background-image: url(/static/images/block.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l2{
            color: crimson;
            position:relative;
            right:320px;
        }
        .ph3{
            background-image: url(/static/images/html.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l3{
            color:crimson;
            position:relative;
            right:330px;
        }
        .ph4{
            background-image: url(/static/images/carbon.png);
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom: 796px;
            background-size: 310px;
            background-repeat: no-repeat;
            
            
        }
        .l4{
            color: crimson;
            position:relative;
            left:250px;
            bottom: 796px;
        }
    
        .ph5{
            background-image: url(/static/images/kotlin.png);
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom:796px;
            background-size: 280px;
            background-repeat: no-repeat;
            
            
        }
        .l5{
            color: crimson;
            position:relative;
            left:250px;
            bottom: 796px;
        }

        .ph6{
            background-image: url(/static/images/php.png);
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom:796px;
            background-size: 280px;
            background-repeat: no-repeat;
            
            
        }
        .l6{
            color: crimson  ;
            position:relative;
            left:250px;
            bottom: 796px;
        }
        .bot{
            text-align:center;
            font-size:larger;
            

        }

        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color:blue; text-decoration: none;"><b>Home</a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: blue; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:blue; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:blue; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Products</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the programming languages that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>Python program<br> Price: 2500.00</b><br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>Blockchain<br> Price: 3000.00</b><br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>HTML<br> Price: 1999.00</b><br<br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>Carbon<br> Price: 6999.00</b><br><br><br><br></p></div>
                    <div class="ph5"></div>
                    <div class="l5"><p align="center"><b>Kotlin<br> Price: 7999.00</b><br><br><br><br></p></div>
                    <div class="ph6"></div>
                    <div class="l6"><p align="center"><b>PHP<br> Price: 5999.00</b><br><br><br><br></p></div>
         
                </div>
                <div class="bot"><p>To Order Online: Call 80 60 40 2004</p></div>

                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by Yuvaranithulasingam</footer></div>
            </div>
        </div>
    </body>
</html>

people.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 2540px;
            width: 85%;
            border: 12px solid lawngreen;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
        color:black;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid blue;
            background-color:white;
            width:98%;
            height:2240px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/images/my.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid red;
            height:200px;
            width:200px;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color:black;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/images/malar.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color:black;
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(/static/images/jonal.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color:black;
            position:center;
            text-align:center;
        }
        
        .amph1{
            background-image: url(/static/images/sasi.png);
            background-size: 250px;
            background-position-x:center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color:black;
            position:center;
            text-align:center;
        }

        .amph2{
            background-image: url(/static/images/keerthi.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color:black;
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(/static/images/vishnu.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
            color:black;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: blue; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: blue; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:blue; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:blue; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>Yuvaranithulasingam</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="right"><b><h2>Panimalar</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p align="left"><b><h2>Jonal</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="right"><b><h2>Sasi devi</h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>keerthana</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="left"><b><h2>Vishnu priya</h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our teaching had made you more to create a new world with TECHNOLOGY.<br> We hope that, we are helping you to develop your programming skills.</div>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by Yuvaranithulasingam</footer></div>
            </div>
        </div>
    </body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
    
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: blue; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: blue; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:blue; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:blue; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        Poonamallee, Chennai, TamilNadu, India.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 14345677</li>
                        <li><b>Mobile</b>: 80 60 40 2004</li>
                        <li><b>Facebook</b>: fb/yuvadeveloping</li>
                        <li><b>Email Id:</b>yuvasoft@gmail.com</li>
                    </ul>
                    <div style="text-align: center;color:red;font-size:20px;"><b>Use our services and Make your bright Future!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by Yuvaranithulasingam</footer></div>
            </div>
        </div>
    </body>
</html>

styles.css

.home{
            height: 700px;
            width: 85%;
            border: 12px solid lawngreen;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .content{
            border:1px solid blue;
            background-color: white;
            width:95%;
            height:400px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .header{
            height: 128px;
            width:100%;
            background-image: url(/static/images/header.png);
            background-size: cover;
            
        }
        .logo{
            height:21%;
            width: 10%;
            position:absolute;
            background-image: url(/static/images/icon.png);
            background-size:cover;
            
        }
        .prod{
            height:auto;
            width:auto;
            position:relative;
            bottom:10px;
            left:550px;
            border:4px solid transparent;
            text-align:center;
            display: inline;
            padding:15px;
            font-family:'Algerian';
            font-size: large;  
        }
        .prod:hover{
            background-color:darkmagenta;
        }
        .people{
            height:auto;
            width:auto;
            position:relative;
            bottom:10px;
            left:700px;
            border:4px solid transparent;
            text-align:center;
            display: inline;
            padding:15px;
            font-family:'Algerian';
            font-size: large;  
        }
        .people:hover{
            background-color:darkmagenta;
        }
        .contact{
            height:20px;
            width:10%;
            position:relative;
            bottom:45px;
            left:1000px;
            border:4px solid transparent;
            text-align:center;
            padding:15px;
            font-family:'Algerian';
            font-size: large;  
        }
        .contact:hover{
            background-color:darkmagenta;
        }
                
        .h{
            height:20px;
            width:10%;
            position:relative;
            top:30px;
            left:200px;
            border:4px solid transparent;
            text-align:center;
            
            padding:15px;
            font-family:'Algerian';
            font-size: large;  
        }
        .h:hover{
            background-color:darkmagenta;
            overflow:hidden;
        }
        .footer{
            border:3px solid gold;
            width:98%;
            height:6px;
            position:relative;
            bottom: 1px;
            background-color: darkmagenta;
            text-align:center;

        }
        .title{
            border:2px solid lawngreen;
            background-color:gold;
            padding:1px;
            width:99.7%;
            height: 70px;
            text-align:center;
            font-family:'Alberian';
            margin-left:auto;
            margin-right: auto;
            
        }
        .content1{
            border:1px solid blue;
            background-color: white;
            width:98%;
            height:100px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;

        }
```
## OUTPUT:
![Output](./out(home).png)
![Output](./out(pro).png)
![Output](./out(people).png)
![Output](./out(con).png)

## HTML VALIDATOR:

![Html validator](./ex7(valid).png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
