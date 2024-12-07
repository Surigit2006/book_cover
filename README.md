# Ex.06 Book Front Cover Page Design
# Date:
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
<html>
    <head>
        <title>book cover</title>
        <style>
            body{
                background-repeat: no-repeat;
                background-size: 40cap;
                background-position: center;
                text-align: center;
                
            }
            .container {
                display: flex;
                justify-content: center; /* Horizontally center */
                align-items: center;    /* Vertically center */
                height: vh;          /* Full screen height */
            }
            
        </style>
    </head>
    {% load static %}
    <body background="{% static '312202de89b7aec6df5a1a1adbbfe546.jpg' %}">
        <br><br><br><br><br><br><br><br>
        <font color="red" size="8">The</font><br>
        <font color="red" size="9">Fairytale</font><br>
        <font color="red" size="3">(love story)</font><br>
        <font color="white" size="3"></font><br><br>
        
        
        <div class="container">
            
            <img src="{% static 'voilinanime.jpg' %}" style="width: 300px; height: 300px;">
        </div>
     
        <h1 style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; color: red;">Suriya</h1>
    </body>
</html>
```
# OUTPUT:

![alt text](<Screenshot 2024-12-07 115940.png>)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
