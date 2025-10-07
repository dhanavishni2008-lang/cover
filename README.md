# Ex.06 Book Front Cover Page Design
## Date:07-10-2025

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
````
book.html

<!DOCTYPE html>
<html>
<head>
    <title>Book Cover</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="cover">
        <div class="border">
            <h3 class="top">SEC Insights</h3>
            <h1>CLOUD COMPUTING FOR<br>AI AND DATA SCIENCE</h1>
            <p class="sub">From data to decisions-powered by the cloud<br>Editor's pick 2025</p>

            <div class="left">
                <h4>FIRST EDITION</h4>
                <div class="name">
                    <p>Dhanavishni M</p>
                </div>
            </div>

            <div class="right">
                <img src="author.jpg" alt="Author Photo">
                <hr class="line">
                <div>
                    <p>SEC</p>
                </div>
            </div>

        </div>
        <hr class="line">
        <div class="div">
        </div>
    </div>
</body>
</html>

style.css

body {
    background-color:lightblue;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.cover {
    width: 400px;
    height: 550px;
    background: url(background.jpg);
    background-size: cover;
    background-position: center;
    position: relative;
    text-align: center;
    color: black;
    font-family: 'Arial Narrow Bold', sans-serif;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

.border {
    border: 2px solid BLACK;
    margin: 30px;
    height: 87%;
    padding: 10px;
    position: relative;
}

.top {
    position: relative;
    bottom: 20px;
    right: 120px;
    margin: 0;
    padding: 6px 8px 6px 0;
    display: inline-block;
    font-size: 16px;
    border-bottom: 1px solid black;
    color: solid black; 
}

h1 {
    font-size: 24px;
    margin-top: 30px;
    font-weight: bold;
}

.sub {
    font-style: Lato italic;
    font-size: 15px;
    margin-top: 20px;
}

.left h4 {
    position: relative;
    top: 200px;
    right: 90px;
    font-size: 20px;
    font-style: PT Sans;
    font-weight: bold;
    margin: 0;
}

.left p {
    position: relative;
    top: 240px;
    right: 100px;
    font-size: 20px;
    margin-top: 5px;
}

.right img {
    position: relative;
    top: 5px;
    left: 90px;
    width: 130px;
    height: 150px;
    border: 2px solid black;
}

.line {
    height: 2px;
    width: 100%;
    background-color: solid black;
}

.right p {
    font-style: initial;
    font-size: larger;
    top: 20px;
    left: 100px;
    margin-top: 5px;
    font-weight: bold;
    position: relative;
}

````

## OUTPUT:
![alt text](<Screenshot (54).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
