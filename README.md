# Ex04 Places Around Me
## Date: 22/09/2025

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
mappping.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body>
        <h1 ALIGN="center">KANCHIPURAM</h1>
        <h2 style="color:brown" align="center">Neha S (25016526)</h2>
        <img src="Screenshot 2025-09-20 141912.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="SBM PARK INN" title="SBM PARK INN" href="park.html" coords="988,283,1172,334" shape="rect">
    <area target="" alt="Nalli silk sarees" title="Nalli silk sarees" href="sarees.html" coords="894,226,51" shape="circle">
    <area target="" alt="Kanchipuram silk house" title="Kanchipuram silk house" href="silksarees.html" coords="1052,435,1303,494" shape="rect">
    <area target="" alt="Marutham Village Resort" title="Marutham Village Resort" href="resort.html" coords="940,646,1105,695" shape="rect">
    <area target="" alt="SS Biriyani shop" title="SS Biriyani shop" href="food.html" coords="1261,622,1167,691,1170,778,1367,778,1367,690" shape="poly">
</map>
    </body>
</html>

food.html
<html>
    <head>
        <title>food</title>
    </head>
    <body bgcolor="orange">
        <h1 style="color:blue;" align="center" bgcolor="pink">KANCHIPURAM</h1>
        <h2 align="center" style="color:purple;">SS HYDERABAD BIRYANI</h2>
        <hr size="5" color="red">
        <font size="10" style="color:darkgreen">SS Hyderabad Biryani is a popular chain of restaurants primarily located in Chennai, Tamil Nadu, India.The restaurant is known for its delicious Hyderabadi biryani, which is a flavorful and aromatic rice dish cooked with basmati rice, meat (usually chicken or mutton), and a blend of rich spices cartoonwise.</font>

    </body>
</html>
 
resort.html
<html>
    <head>
        <title>resort</title>
    </head>
    <body bgcolor="yellow">
        <h1 style="color:brown;" align="center">KANCHIPURAM</h1>
        <h2 align="center" style="color:orangered;">Marutham Village Resort</h2>
        <hr size="5" color="teal">
        <font size="10" style="color:blue">The Marutham village resort is more than just a rustic retreat. It is an intentional return to simplicity, designed to replicate the ambiance and lifestyle of traditional rural life while maintaining modern comforts.It attracts people of all ages.</font>
    </body>
</html>
 
silksarees.html
<html>
    <head>
        <title>silksarees</title>
    </head>
    <body bgcolor="pink">
        <h1 style="color:purple;" align="center">KANCHIPURAM</h1>
        <h2 align="center" style="color:green;">Kanchipuram Silk House</h2>
        <hr size="5" color="yellow">
        <font size="10" style="color:brown;">Kanchipuram Silk House is an establishment associated with the production and sale of authentic Kanchipuram silk sarees, a renowned type of handwoven silk originating from the city of Kanchipuram in Tamil Nadu, India. These sarees are known for their rich, vibrant colors, intricate designs often inspired by temple architecture, and the use of pure mulberry silk and genuine zari (gold or silver threads). </font>
    </body>
</html>

sarees.html
<html>
    <head>
        <title>sarees</title>
    </head>
    <body bgcolor="lavendar">
        <h1 style="color:red;" align="center">KANCHIPURAM</h1>
        <h2 align="center" style="color:darkblue;">Nalli Silk Sarees</h2>
        <hr size="5" color="yellow">
        <font size="10" style="color:brown;">Kanchipuram Silk House is an establishment associated with the production and sale of authentic Kanchipuram silk sarees, a renowned type of handwoven silk originating from the city of Kanchipuram in Tamil Nadu, India. These sarees are known for their rich, vibrant colors, intricate designs often inspired by temple architecture, and the use of pure mulberry silk and genuine zari (gold or silver threads). </font>
    </body>
</html>

park.html
<html>
    <head>
        <title>park</title>
    </head>
    <body bgcolor="midnightblue">
        <h1 style="color:burlywood;" align="center">KANCHIPURAM</h1>
        <h2 align="center" style="color:aqua;">SBK PARK INN</h2>
        <hr size="5" color="grey">
        <font size="10" style="color:coral;">SBK park inn offers you world of hospitality filled with grand tradition, culture, heritage and service at moderate tariffs ensuring value for money. The Hotel makes guests feel at home, ensuring continued patronage. SBK Park Inn has a fresh, modern air geared rooms to make your stay truly exceptional. It is cutting edge in style of "Temples and Silk Sarees" . Expect visually entertaining interiors with contemporary amenities , reflecting the urban glamor of Kanchipuram City.</font>
</html>

```

## OUTPUT


![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (20).png>) 
![alt text](<Screenshot (21).png>) 
![alt text](<Screenshot (22).png>) 
![alt text](<Screenshot (23).png>) 
![alt text](<Screenshot (24).png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
