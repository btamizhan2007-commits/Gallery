# Ex.08 Design of Interactive Image Gallery
# Date: 13/10/2025
# Ref no: 25018064
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :

```

gallery.html
<html>
    <head>
        <title>Gallery</title>
        <link rel="stylesheet" href="style1.css">
        <script src="style2.js"></script>
    </head>
    <body>
        <h1>MY GALLERY - Tamizhan b (25018064)</h1>
        <div class="gallery">
            <div class="galleryitem">
                <img class="zoom" src="gallery1.jpg" onmouseover="mousein()" onmouseout="mouseout()" id="Photo">
            </div>
            <div class="galleryitem">
                <img class="zoom" src="gallery2.jpg" onmouseover="mousein()" onmouseout="mouseout()" id="Photo">
            </div>
            <div class="galleryitem">
                <img class="zoom" src="gallery3.jpg" onmouseover="mousein()" onmouseout="mouseout()" id ="photo">

            </div>
            <div class="galleryitem">
                <img class="zoom" src="gallery4.jpg" onmouseover="mousein()" onmouseout="mouseout()"id="photo">

            </div>
            <div class="galleryitem">
                <img class="zoom" src="gallery5.jpg" onmouseover="mousein()" onmouseout="mouseout()" id="Photo">
            </div>
        </div>
        <footer class="copyrights">
            &copy; TAMIZHAN B (25018064)
        </footer>
    </body>
</html>

style1.css
body {
    background-color: rgb(133, 16, 35);
    text-align: center;
    margin-top: 50px;
}

.gallery {
    display: flex;
    gap: 20px;
    padding-top: 50px;
    justify-content: center;;
}

.galleryitem {
    cursor: pointer;
    text-align: center;
    width: 200px;
    padding: 20px;
}

.galleryitem img {
    width: 230px;
    height: 300px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: rgb(176, 51, 162);
    text-align: center;
    top: 130px;
    left: -20px;
    position: relative;
}

style2.js
style2.js

function mousein()
{
    document.getElementById("Photo").style.width="250";
    document.getElementById("Photo").style.height="350";
}

function mouseout()
{
    document.getElementById("Photo").style.width="230";
    document.getElementById("Photo").style.height="300";
    
 }

```
# OUTPUT:
![gallery1](https://github.com/user-attachments/assets/b9082e63-0a93-4de3-90dd-41b82d6cc0cf)

![gallery2](https://github.com/user-attachments/assets/dea74909-975a-4d0b-a5ea-bc523184f175)

![gallery3](https://github.com/user-attachments/assets/081cd58a-47a7-481a-8e68-fb57c93cb48b)

![gallery4](https://github.com/user-attachments/assets/593e4778-2fa2-4bfc-b294-5a81a074fe69)

![gallery5](https://github.com/user-attachments/assets/9c2f49fb-900e-4fa7-9e9a-6d2829858135)


# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
