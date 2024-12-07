# Ex.06 Book Front Cover Page Design
# Date:11/11/2024
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

# PROGRAM:sudharsan.s (24009664)
                    ```
DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            background-color: #e0e0e0; /* Light gray background */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Arial', sans-serif;
            border: 10px solid #2980b9; /* Blue border around the body */
            padding: 20px; /* Padding around the content */
            box-sizing: border-box; /* Include padding in dimensions */
        }

        .book-cover {
            background-color: black;
            border: 10px solid white;
            border-radius: 15px;
            box-shadow: 0 20px 80px rgba(0, 0, 0, 0.5);
            width: 320px;
            padding: 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .book-header {
            font-size: 24px; /* Updated font size */
            font-weight: bold;
            color: #2c3e50;
            background: linear-gradient(45deg, #2980b9, #6dd5ed);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin: -10px -20px 20px -20px;
            padding: 10px 0;
            border-radius: 10px 10px 0 0;
        }

        .book-title {
            font-size: 22px;
            font-weight: bold;
            color: rgb(255, 0, 153);
            margin: 10px 0;
        }

        .book-author {
            font-size: 18px;
            color: white;
            margin: 10px 0 20px 0;
        }

        .book-image img {
            max-width: 100%;
            border-radius: 18px;
            border: 5px solid skyblue; /* Sky blue border around the image */
            transition: transform 0.3s;
        }

        .book-image img:hover {
            transform: scale(1.05);
        }

        .book-description {
            font-size: 14px;
            color: white;
            margin-top: 15px;
            line-height: 1.5;
        }

        .footer {
            font-size: 16px;
            color: white;
            position: absolute;
            bottom: 16px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #2980b9; /* Background for footer */
            padding: 5px 10px; /* Padding for better appearance */
            border-radius: 5px; /* Rounded corners for footer */
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="book-header">EXPERT INSIGHT</div>
        <div class="book-title">Responsive Web Design With HTML5 and CSS</div>
        <div class="book-image">
            <img src="C:\Users\sudharshan\Downloads\book cover.jpg" alt="Book Cover Image">
        </div>
        <div class="book-description">
            <p>Develop future-proof responsive websites using the latest HTML5 and CSS techniques.</p>
        </div>
        <div class="book-author">Ben Frain</div>
        <div class="footer">© 2024 Publishing House</div>
    </div>
</body>
</html>
                    ```

# OUTPUT:!
![Screenshot 2024-11-25 140247](https://github.com/user-attachments/assets/7fa9b467-85d2-41ab-a4fb-9ff3d5c1c99e)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
