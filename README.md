# Ex.06 Book Front Cover Page Design

### Name: Loshini G 
### Register No: 212223220051
## Date:

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
```py
<!DOCTYPE html>
<html>
<head>
  <style>
    .image {
      margin-left: 450px;
      margin-top: 25px;
    }

    .img2 {
      filter: brightness(50%);
      opacity: 95%;
    }

    .h1 {
      position: absolute;
      top: 45px;
      left: 470px;
      font-style: italic;
      font-size: large;
      color: azure;
    }

    .line1 {
      position: absolute;
      top: 65px;
      left: 460px;
    }

    .para {
      position: absolute;
      top: 100px;
      left: 500px;
      font-size: larger;
      font-weight: bold;
      color: cornsilk;
      line-height: 20px;
    }

    .para2 {
      position: absolute;
      top: 220px;
      left: 500px;
      font-size: large;
      font-style: italic;
      color: bisque;
      line-height: 15px;
    }

    .line3 {
      position: absolute;
      bottom: 90px;
      left: 460px;
    }

    .edition {
      position: absolute;
      bottom: 85px;
      left: 465px;
      font-style: oblique;
      font-size: large;
      color: aqua;
      line-height: 10px;
    }

    .imgaut {
      position: absolute;
      bottom: 95px;
      left: 938px;
    }

    .name {
      position: absolute;
      bottom: 45px;
      left: 465px;
      font-size: large;
      font-weight: bold;
      color: aquamarine;
    }
  </style>
</head>
<body>
  <div class="image">
    <div class="img2">
      <img src="C:\Users\admin\OneDrive\Documents\cloud.jpg" alt="Cloud Data Image" width="600" height="670">
    </div>
    <div class="h1">Expert Insight</div>
    <div class="line1">
      <hr width="120px" height="30px" color="red">
    </div>
    <div class="para">
      <h1>ARCHITECTING</h1>
      <h1>THE CLOUD</h1>
      <hr width="500px" height="50px" color="white">
    </div>
    <div class="para2">
      <h2>Design Decisions for</h2>
      <h2>Cloud Computing</h2>
      <h2>Service Models</h2>
    </div>
    <div class="edition">
      <h3>First Edition</h3>
    </div>
    <div class="line3">
      <hr width="597px" height="100px" color="orange">
    </div>
    <div class="imgaut">
      <img src="C:\Users\admin\OneDrive\Documents\father of cloud.jpg" alt="Author Image" width="120" height="120">
    </div>
    <div class="name">
      <h4><strong>LOSHINI.G</strong></h4>
    </div>
  </div>
</body>
</html>
```
## OUTPUT:
![Screenshot 2024-11-07 115404](https://github.com/user-attachments/assets/c3568513-74b6-443b-8fd5-9ec3bceb15b8)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
