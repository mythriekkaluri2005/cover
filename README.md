# Ex.06 Book Front Cover Page Design
## Date: 27-04-2024

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
```
book.html

<!DOCTYPE html>
<html>

<head>
    <title>WEB APPLICATIONS</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(background.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(231, 9, 190);
            top:270px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(240, 240, 11);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:rgb(243, 56, 4);
            font-size: medium;
            position: relative;
            top:235px;
            left:330px;
        }
        .ed{
            color:rgb(15, 184, 184);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:190px;
        
        }
        .subtitle{
            color:rgb(14, 239, 78);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                AIML
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>PRACTICAL WEB DESIGN</h1></div>
            <div class="subtitle">
                 LEARN THE FUNDAMENTALS OF WEB DESIGN WITH HTML,CSS,BOOTSTRAP.
                 
            </div>
            <div class="subtitle">
                
            </div>

            <div class="mypic">
                <img src="MyPic.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>EKKALURI MYTHRI</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
</html>

```


## OUTPUT:
![alt text](<Screenshot (13).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
