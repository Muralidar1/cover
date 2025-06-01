# Ex.06 Book Front Cover Page Design
## Date:15\05\25

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
book.html
```
<html>
    <head>
        <title>Simple in Silence</title>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
        <div class="cover">
            <h1 class="title">Simple in Silence </h1>
            <p class="p1">"A boy's quiet journey to self-discovery. Simple in Silence speaks through SILENCE."</p>
            <span class="badge">First Edition</span>
            <div>
                <p class="author">Author: Muralidar</p>
                <p class="public">Publication: SEC</p>
            </div>
            <div class="logo">
                <img src="sec logo.png" alt="logo" class="img">
            </div>
            <div class="a1">
                <p class="p3">Walk through the life of the boy</p>
            </div>
            <div class="a2">
                <p class="p4"># Best Selling, 1 Billion copies sold</p>
            </div>
            <div class="auth">
                <img src="author.png" alt="auimage" class="au">
            </div>
        </div>
    </body>
</html>
```
style.css
```
body{
    background-color: black;
}

.cover{
    flex-direction: column;
    align-items: center;
    width: 550px;
    height: 740px;
    margin: auto;
    background-color: aliceblue;
    padding: 20px;
    background-image:url(SIS.jpeg);
    background-size: cover;
    background-position: center;
    background-repeat:no-repeat ;
    box-sizing: border-box;
    position: relative;

}

.title{
    text-align: center;
    margin: 0;
    padding: 0;
    margin-bottom: 20px;
    color: white;
    font-size: 70px;
    letter-spacing: -4px;
    -webkit-text-stroke: 2px rgb(0, 0, 0);
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: white;
    font-weight: bold;

}
.badge {
  background-color: gold;
  color: black;
  padding: 3px 10px;
  border-radius: 20px;
  font-size: 20px;
  text-align: center;
  width: fit-content;
  display:block;
  margin: 10px auto;
  font-family: ink free;
  font-weight: bolder;
}


.p1{
    text-align: center;
    margin-top: -10px;
    line-height: 1;
    font-size: 20px;
    font-family: monospace;
    font-weight: bolder;

}

.p2{
    text-align: center;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-size: x-large;
    color: blue;
}

.author{
    text-align: right;
    margin-top: 10px;
    position: absolute;
    bottom: 10px;
    right: 10px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: black;
    font-weight: bolder;
    font-size: x-large;
    background-color: rgba(240, 255, 240, 0.8);
    border-radius: 20000px;
    text-shadow: 2px 2px 2px rgba(0,0,0,0.4);
}

.public{
    text-align: left;
    margin-top: 10px;
    position: absolute;
    bottom: 10px;
    left: 10px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: black;
    font-weight: bolder;
    font-size: x-large;
    background-color: rgba(240, 255, 240, 0.8);
    border-radius: 20000px;
    text-shadow: 2px 2px 2px rgba(0,0,0,0.4);

}

.logo {
    position: absolute;
    bottom: 70px;
    left: 40px;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    border: 3px solid black;
    display: flex;  
    justify-content: center;
    align-items: center;
    overflow: hidden;
}

.logo img {
    width: 1000%;
    height: 100%;
    object-fit: contain;
    border-radius: 50%;
}

.a1{
    position: absolute;
    bottom: 400px;
    height: 40px;
    
}

.p3{
    position: absolute;
    left:40px;
    font-weight: bolder;
    font-family: Ink Free;
    font-size: 25px;
    color: white ;
    transform: rotate(-15deg);
    -webkit-text-stroke: 2px rgb(0, 0, 0);
}

.a2{
    position: absolute;
    bottom: 400px;
    height: 40px;
    
}

.p4{
    position: absolute;
    left:400px;
    color: white;
    font-weight: bolder;
    font-family: ink free;
    font-size: 25px;
    transform: rotate(15deg);
    -webkit-text-stroke: 2px rgb(0, 0, 0);
}

.auth {
    position: absolute;
    bottom: 70px;
    left: 400px;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    border: 3px solid black;
    display: flex;  
    justify-content: center;
    align-items: center;
    overflow: hidden;
}

.au {
    width: 1000%;
    height: 100%;
    object-fit: contain;
    border-radius: 50%;
}


```

## OUTPUT:
![Screenshot (7)](https://github.com/user-attachments/assets/b5b4cf89-6274-4885-94ed-e7c2a287c5b2)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
