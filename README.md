# Ex03 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title>map</title>
    </head>
    <body>
        <h1 align="center" style="color:red;">Theni</h1>
        <h2 align="center" style="color:blue;">Khovarthan (25012253)</h2>
        <hr>
        <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Naturals Salon" title="Naturals Salon" href="naturals.html" coords="252,249,406,287" shape="rect">
    <area target="" alt="SSK HOUSE" title="SSK HOUSE" href="SSK.html" coords="838,487,64" shape="circle">
    <area target="" alt="Jazz Fitness Studio" title="Jazz Fitness Studio" href="Fitness.html" coords="96,361,335,423" shape="rect">
    <area target="" alt="Menaka mills " title="Menaka mills " href="Mills.html" coords="531,170,636,213,636,289,420,294,417,213" shape="poly">
    <area target="" alt="Arulmigu Sri sadaiyandi Temple" title="Arulmigu Sri sadaiyandi Temple" href="Sadaiyandi.html" coords="917,150,1051,177,1055,249,804,243,800,179" shape="poly">
</map>
    </body>
</html>

<html>
    <head>
        <title>Fitness.html</title>
        <body bgcolor="red">
            <h1 align="center" style="color:red;">Theni</h1>
            <h2 align="center" style="color:blue;">Khovarthan (25012253)</h2>
            <hr>
            Jazz Fitness Studio is a fitness center with multiple locations in Madurai, India, offering a variety of classes like cardio, Zumba, and functional training, along with gym facilities, personal training, and group workouts.
        </body>
    </head>
</html>

<html>
    <head>
        <title>Mills.html</title>
        <body bgcolor="lightblue">
            <h1 align="center" style="color:red;">Theni</h1>
            <h2 align="center" style="color:blue;">Khovarthan (25012253)</h2>
            <hr>
            Menaka Mills is a vertically integrated textile manufacturer based in Theni, Tamil Nadu, specializing in synthetic knits like polar fleece, as well as blankets and apparel. The company handles the entire manufacturing process, from knitting and dyeing to finishing
        </body>
    </head>
</html>

<html>
    <head>
        <title>naturals.html</title>
        <body bgcolor="aqua">
            <h1 align="center" style="color:red;">Theni</h1>
            <h2 align="center" style="color:blue;">Khovarthan (25012253)</h2>
            <hr>
            Naturals Salon is India's largest salon chain, known for offering a wide range of professional and affordable beauty services in a hygienic environment.
        </body>
    </head>
</html>

<html>
    <head>
        <title>Sadaiyandi.html</title>
        <body bgcolor="yellow">
            <h1 align="center" style="color:red;">Theni</h1>
            <h2 align="center" style="color:blue;">Khovarthan (25012253)</h2>
            <hr>
            The Arulmigu Sri Sadaiyandi Temple (also known as Sri Sadaiyandi Munieewswarar Temple) is a temple dedicated to Sri Sadaiyandi Munieswarar, located in Athoor, Tamil Nadu, and can be found on Sri Sadaiyandi Koil Road. While a detailed description of its architecture is not available, it is identified as a significant religious site in the area, with its location on the aforementioned road noted by local guides. 
        </body>
    </head>
</html>

<html>
    <head>
        <title>SSK.html</title>
        <body bgcolor="Purple">
            <h1 align="center" style="color:red;">Theni</h1>
            <h2 align="center" style="color:blue;">Khovarthan (25012253)</h2>
            <hr>
            "SSK House" can refer to several different properties, including guest houses and an architectural project, so the specific description depends on which one is being sought. For accommodation, it could be S.S.K Residency in Chennai, which offers air-conditioned rooms near the airport and trade center, or SSK Rooms in Gūduvāncheri, which provides rooms with balconies and lake views. 
        </body>
    </head>
</html>
```

## OUTPUT

![alt text](<Screenshot (32).png>)

![alt text](<Screenshot (33).png>)

![alt text](<Screenshot (34).png>)

![alt text](<Screenshot (35).png>)

![alt text](<Screenshot (36).png>)

![alt text](<Screenshot (37).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.