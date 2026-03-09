# Product Card Design with Hover Effect using CSS
## Date:

## AIM:
To design a Product Card for an E-commerce website using HTML and CSS and apply hover effects, transitions, and styling techniques to create an interactive user interface.

## DESIGN STEPS:

### Step 1:
Create a basic HTML structure using ```<!DOCTYPE html>, <html>, <head>, and <body>```.

### Step 2:
Add a container div for the product card.

### Step 3:
Insert the product image using the ```<img>``` tag.

### Step 4:
Add product name, description, and price using ```<h3>``` and ```<p>``` tags.

### Step 5:
Create an Add to Cart button using the ```<button>``` tag.

### Step 6:
Style the product card using CSS by applying:
<ul>
  <li>width</li>
  <li>padding</li>
  <li>border-radius</li>
  <li>box-shadow</li>
</ul>

### Step 7:
Align the card content using text-align and spacing properties.

### Step 8:
Add hover effects using :hover selector.

### Step 9:
Apply transform: translateY() to move the card slightly upward on hover.

### Step 10:
Increase the box-shadow to create a lifting effect.

### Step 11:
Add transform: scale() to slightly zoom the product image on hover.

### Step 12:
Apply transition property to make the hover animation smooth.

### Step 13:
Create a footer section at the bottom of the page.

### Step 14:
Display Learner Name and Register Number inside the footer.

### Step 15:
Style the footer using background color and center alignment.

### Step 10:
Test your webpage in a browser.

## PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
<style>
body{font-family:Arial;text-align:center;background:#f2f2f2}

.card{width:300px;margin:80px auto;padding:15px;background:#fff;
border-radius:10px;transition:0.3s;box-shadow:0 4px 8px gray}

.card:hover{transform:translateY(-8px);box-shadow:0 10px 20px gray}

.card img{width:100%;transition:0.3s;border-radius:10px}

.card:hover img{transform:scale(1.1)}

button{padding:8px 15px;background:blue;color:white;border:none;transition:0.3s}

.card:hover button{background:orange}

footer{background:black;color:white;padding:10px;margin-top:40px}
</style>
</head>

<body>

<div class="card">
<img src="https://via.placeholder.com/300">
<h3>Smart Watch</h3>
<p>Fitness watch</p>
<h4>₹2999</h4>
<button>Add to Cart</button>
</div>

<footer>
Learner Name: Shylash A | Register Number: IT-25018785
</footer>

</body>
</html>
```
## OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/08f6319e-b8ca-4ae1-bc64-4420a422e768" />


## RESULT:
The Product Card with Hover Effect was successfully designed using HTML and CSS.
