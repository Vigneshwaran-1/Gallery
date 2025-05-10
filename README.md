# Ex.08 Design of Interactive Image Gallery
# Date:7/5/25
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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      margin: 0;
      padding: 0;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
      padding: 20px;
    }

    .gallery img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s ease;
      cursor: pointer;
    }

    .gallery img:hover {
      transform: scale(1.1);
    }
  </style>
</head>
<body>

  <div class="gallery">
    <img src="http://wonderfulengineering.com/wp-content/uploads/2016/01/nature-wallpapers-8.jpg" alt="Image 1">
    <img src="https://picjumbo.com/wp-content/uploads/beautiful-nature-scenery-free-photo-2210x1473.jpg" alt="Image 2">
    <img src="https://images.pexels.com/photos/459225/pexels-photo-459225.jpeg?cs=srgb&dl=daylight-environment-forest-459225.jpg&fm=jpg" alt="Image 3">
    <img src="http://wonderfulengineering.com/wp-content/uploads/2016/01/nature-wallpapers-38.jpg" alt="Image 4">
    <img src="https://wallpaperaccess.com/full/256070.jpg" alt="Image 5">
  </div>

</body>
</html>
~~~
# OUTPUT:
![Screenshot 2025-05-10 122643](https://github.com/user-attachments/assets/555eb1fd-926f-4d3c-b9e3-23f6845fadb5)

# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
