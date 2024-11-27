# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
 <head>
 <title>MyCity</title>
 </head>
 <body>
<h1 align="center">
 <font color="blue"><b>Thirupattur</b></font>
 </h1>
 <h3 align="center">
 <font color="Yellow">Lokeshwaran R  (24011606)</font>
 </h3>
 <center>
 <img src="image.png" usemap="#MyCity">
 

 <map name="MyCity">
    <area target="" alt="Green trends" title="Green trends" href="green.html" coords="681,86,877,131" shape="rect">
    <area target="" alt="Poorvika" title="Poorvika" href="poorvika.html" coords="678,333,892,390" shape="rect">
    <area target="" alt="Sathiya" title="Sathiya" href="sathiya.html" coords="551,248,747,283" shape="rect">
    <area target="" alt="Reliance" title="Reliance" href="reliance.html" coords="410,636,564,723" shape="rect">
    <area target="" alt="Bru" title="Bru" href="bru.html" coords="223,434,443,496" shape="rect">
    <area target="" alt="CKC" title="CKC" href="ckc.html" coords="728,667,928,735" shape="rect">
</map>
</center>
</body>
</html>



















```


## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
