# Design a Website for Server Side Processing

# AIM:

To design a website to perform mathematical calculations in server side.

# DESIGN STEPS:

## Step 1:
Clone the repository from GitHub
## Step 2:
Create Django Admin project.
## Step 3:
Create a New App.
## Step 4:
Sync forkCreate python programs for views and urls.
## Step 5:
Create a HTML file of forms.
## Step 6:
Publish the website in the given URL.



# program
```
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Rectangle</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body
{
background-color:rgb(150, 149, 149)
}
.edge
{
width: 1080px;
margin-left:auto;
margin-right:auto;
padding-top:200px;
padding-left:300px;
}
.box
{
display:block;
border:Thick dashed red;
width:500px;
min-height:300px;
font-size:20px;
background-color:rgba(90, 29, 102, 0.8);
}
.formelt{
color: rgb(22, 19, 19);
text-align:center;
margin-top:5px;
margin-bottom:5px;
}
h1
{
color: yellow;
text-align:center;
padding-top:20px;
}
</style>
</head><body>
<div class="edge">
<div class="box">
<h1>Area of a Rectangle</h1>
<form method="POST">
{%csrf_token %}
<div class="formelt">
Length:<input type="text" name="length" value="{{l}}"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth:<input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area:<input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>
```
# output

<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Rectangle</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body
{
background-color:rgb(150, 149, 149)
}
.edge
{
width: 1080px;
margin-left:auto;
margin-right:auto;
padding-top:200px;
padding-left:300px;
}
.box
{
display:block;
border:Thick dashed red;
width:500px;
min-height:300px;
font-size:20px;
background-color:rgba(90, 29, 102, 0.8);
}
.formelt{
color: rgb(22, 19, 19);
text-align:center;
margin-top:5px;
margin-bottom:5px;
}
h1
{
color: yellow;
text-align:center;
padding-top:20px;
}
</style>
</head><body>
<div class="edge">
<div class="box">
<h1>Area of a Rectangle</h1>
<form method="POST">
{%csrf_token %}
<div class="formelt">
Length:<input type="text" name="length" value="{{l}}"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth:<input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area:<input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>


# RESULT:

The program is executed succesfully
