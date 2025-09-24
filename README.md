# Ex.06 Book Front Cover Page Design
# Date:24.09.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

 <title>Book Cover</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background:#f5f5f5
        }

        .book-cover {
            width: 550px;
            height: 850px;
            background-color:plum;
            box-sizing: border-box;
            text-align: center;
            padding:0%;
            position: relative;
            box-shadow: 0 8px 15px rgba(0,0,0,0.4);
        }

        .title {
            font-size: 28px;
            font-weight: bold;
            margin-top:90px;
            line-height:1.9;
            
        }
        .author {
            position: absolute;
            bottom: 20px;
            left: 20px;
            display: flex;
            align-items: center;
            color:white;
        }
        .author img {
            width: 60px;
            height: 60px;
            border-radius: 50;
            margin-right: 10px;
        }
        .background img {
            position : absolute;
            bottom: 60px;
            left: 0;
            right: 0;
            height: 100px;
            background-image:url('c:\Users\acer\Pictures\Screenshots\Screenshot 2025-09-23 144857.png') no-repeat center ;
            background-size:100px;
            opacity: 0.6;
        }
    </style>
    </head>
<body>
    <div class="book-cover">
        <div class="title"align="margin-top">OUR UNIVERSE</div> 
        <div class="background img"></div>
        <div><h2>Milkyway Galaxy<h2></div>
        <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-09-23 193000.png"width="500px" height="700px">
        <div class="author">
            <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-09-23 191855.png" alt="Author">
            <span>Andrew Cohen</span>
        </div>
    </div>
</body>
</html>








```
# OUTPUT:
![alt text](<Screenshot 2025-09-24 085130.png>)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
