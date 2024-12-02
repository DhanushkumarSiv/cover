# Ex.06 Book Front Cover Page Design
## Date:02/12/2024

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
cover.html

<html>
    <head>
<style>
.intro
{
    position: relative;
display: block;
margin-left: 35%;
margin-right: 50%;
    width: 300px;
    height: 300px;
}
.maincover
{
   
  
    width: 260%;
    height: 280%;
  
}
.user
{
    position: absolute;
    bottom: -450px;
    right: -475px;
    width: 170px;
    height: 230px;
    border-radius: 7px;
    border: 4px solid white;
}
.maintitle
{
    position: absolute;
   top: 2px;
   left: 300px;
   color: whitesmoke;
   font-style: italic;
    font-size: 80px;
}
.subtitle{
    position: absolute;
    top:380px;
    left:250px;
    color:red;
    font-style: unset;
    font-size: 40px;
}
.copub{
    position: absolute;
    top: 750px;
    left: 520px;
    color: aliceblue;
    font-style: normal;
    font-size: 20px;
}
.author
{
    position: absolute;
    top: 750px;
    right: 90px;
    color: aliceblue;
    font-style: normal;
    font-size: 20px;
}
.edition
{
    position: absolute;
    top: 680px;
    right: 110px;
    color: white;
    font-style: normal;
    font-size: 20px;
}
.publisher
{
    position: absolute;
    top: 755px;
    left:650px;
    color: aliceblue;
    font-style: inherit;
    font-size: 30px;
    font-style: bold;
}



</style>
    </head>
    <body bgcolor="tan">
        <div class="intro">
            <img src="book cover.png" class="maincover">
            <img src="dhanush image.jpg" class="user">
            <h1 class="maintitle">LET US C</h1>
            <h2 class="subtitle">Functions & Algorithm</h2>
            <p class="edition">FOURTH EDITION</p>
            <p class="copub">Published by :</p>
            <p class="author"><b>DHANUSHKUMAR .S</b></p>
            <p class="publisher">SEC</p>
            
        </div>
    </body>
</html>

```


## OUTPUT:

![alt text](<cover output.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
