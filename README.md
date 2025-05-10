# Ex.08 Design of Interactive Image Gallery
## Date:10/5/25c

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
<title>
Interactive Image Gallery
</title>
<style>
body
{
font-family: Arial, sans-serif;
display: flex;
flex-direction: column;
align-items: center;
margin: 0;
background-size: cover;
background-image: url("background img.jpeg")
}
h6
  {
margin-top: 20px;
color: rgb(203, 24, 227);
font-size: xx-large;
font-style: bold;
}
.Gallery
{
display: flex;
gap: 15px;
max-width: 800px;
margin-top: 20px;
justify-content: center;
}
</style>
<body>
<h6>MOST EXPENSIVE CAR COLLECTION</h6>
<div class="Gallery">
<img src="web ex-8 1.jpeg" width="400" height="400" onclick="ope
<img src="web ex-8 2.jpeg" width="400" height="400" onclick="ope
<img src="web ex-8 3.jpeg" width="400" height="400" onclick="ope
<img src="web ex-8 4.jpeg" width="400" height="400" onclick="ope
<img src="web ex-8 5.jpeg" width="400" height="400" onclick="ope
<p></p>
</div>
<script>
function openImage(src) {
window.open(src, "_blank");
}
</script>
</body>
</html>
```

## OUTPUT:
![alt text](Buda.webp)
![alt text](lavender.jpg)
![alt text](paris.jpg)
![alt text](porsche.jpg)
![alt text](seafood_spaghetti.jpg)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
