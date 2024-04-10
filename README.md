# Ex.06 Book Front Cover Page Design
## Date:05.04.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```c
<!DOCTYPE html>
<html>

<head>
    <title>SCIENCE</title>
    <style>
        .bookpage{

            width: 457px;
            height: 690px;
            color:rgb(15, 13, 13);
            margin-left: auto;
            margin-right: auto;
            padding: -20px;
            font-family: ' Arial, sans-serif';
            background-image: url(sta5.jpg);
            background-size: cover;
        }
            
        
        .insight{
            top: 10px;
            left: 15px;
            display: inline;
            position: relative;
            color:rgb(9, 189, 189);
            font-family: Harrington;
            
        }
        
        
        .hrstyle{
            top: 8px;
            position: relative;
            width: 105px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(216, 227, 180);
            top: 300px;
            left: -170px;
            font-family:Harrington;
            font-size: medium;
        }
        .booktitle{
            color:rgb(169, 217, 217);
            font-family:algerian;
            font-size: large;
            text-align: center;
            position: relative;
            top: 26px;
        
        }
        .id {
            width: 100px;
            color:rgb(0, 5, 5);
            position: relative;
            top: 310px;
            
        }
        .pub{
            color:rgb(231, 191, 191);
            font-size: large;
            font-family: algerian;
            position: relative;
            top:270px;
            left: 110px;
        }
        .ed{
            color:rgb(203, 229, 12);
            font-size: medium;
            font-family:Harrington;
            position:relative;
            top: 200px;
            left:-160px;
        
        }
        .subtitle{
            color:rgb(229, 234, 234);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top: 7px;
        }
        .mypic{
            position: relative;
            top: 260px;
            left: 340px;
            width: 70px;
            height: 80px;
            border-radius: 500px;

        }
        </style>
        <title>BLACKHOLE</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                SCIENCE & TECHNOLOGY
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>ARTIFICAIL INTELLIGENT DIGITAL ASSISSTANT<br>
            <div class="subtitle">
                 BIG EDITION
            </div>
            <div class="subtitle">
                 FUTURE AI ASSISSTANT
            </div>

            <div class="mypic">
                <img src="AVIN5.png" width="110" height="150" >
            </div>
            <div class="id">
                <hr style="color:rgb(143, 177, 109)">
            </div>
            <div class="author">
                AVINASH T
            </div>
            <div class="pub">
                BLOOMSBURY PUBLISHERS
            </div>
            <div class="ed">
                    <b>MODERN WORLD</b> 
            </div>
            <div class="ed">
                     <b>TECHNOLOGY</b>
            </div>
        </body>
        

</html>
```

## OUTPUT:
![alt text](<Screenshot (14).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
