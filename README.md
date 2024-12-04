# Ex04 Places Around Me
## Date: 01/12/2024

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
    <title>My City</title>
</head>

<body>
    <h1 aligen="center" <font align="center" color="red"><b>Rajapalayam</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>MAHALINGA JEYANTH V(24900649)</b></font>
    </h3>
    <center>

        <img src="map.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="chatrapatti" title="chatrapatti" href="chatrapatti.html" coords="1000,778,1111,852"
                shape="rect">
            <area target="" alt="pskumaraswamyraja nagar" title="pskumaraswamyraja nagar"
                href="pskumaraswamyraja nagar.html" coords="1198,655,69" shape="circle">
            <area target="" alt="avarampatti" title="avarampatti" href="avarampatti.html"
                coords="950,700,913,539,1052,545,1089,589,1049,658,902,650" shape="poly">
            <area target="" alt="rr nagar" title="rr nagar" href="rr nagar.html" coords="825,837,74" shape="circle">
            <area target="" alt="samusigapuram" title="samusigapuram" href="samusigapuram.html" coords="954,352,808,264"
                shape="rect">
        </map>
    </center>
</body>

</html>

avarampatti.html
<html>

<body bgcolor="lightgray">
    <font>
        <h1 align="center">avarampatti</h1>
    </font>
    <font align="center" size="5">
        <p>
            <br>
        Agriculture: The primary occupation in Avarampatti is farming, with locals cultivating crops such as paddy, sugarcane,
        and groundnuts.
        Cultural Heritage: Traditional Tamil festivals like Pongal and Deepavali are celebrated with enthusiasm, reflecting the
        rich cultural heritage of the area.
        Community Life: The village promotes a close-knit community where people live harmoniously, often participating in local
        social and religious events.
        Natural Beauty: Surrounded by lush green fields and natural landscapes, Avarampatti offers a peaceful environment away
        from the hustle and bustle of urban areas.
        </p>
    </font>
</body>

</html>

chatrapatti.html
<html>

<body bgcolor="lightgreen">
    <font>
        <h1 align="center">chatrapatti</h1>
    </font>
    <font align="center" size="5">
        <p>
            <br>

            Likely a smaller settlement within the virudhunagar district, close to the historical town of rajapalayam.
            This village may focus on bandages as its primary livelihood, and exported other countries.
        </p>
    </font>
</body>

</html>

rrnagar.html

<html>

<body bgcolor="lightgray">
    <font>
        <h1 align="center">rrnagar</h1>
    </font>
    <font align="center" size="5">
        <p>
            <br>
            rr nagar is also known as ramaswamyraja nagar,and it is located in the virudhunagar district of Tamil
            Nadu.It is known for its many
            cotton bandage industry and is home to several small and medium-scale cotton products units.The village has
            a rich cultural heritage.
        </p>
    </font>
</body>

</html>

pskumaraswamyraja nagar.html
<html>

<body bgcolor="lightred">
    <font>
        <h1 align="center">pskumaraswamyraja nagar</h1>
    </font>
    <font align="center" size="5">
        <p>
            <br>

            pskumaraswmyraja nagar is a village located in the virudhunagar district of Tamil Nadu, India. It is known
            for its many
            cotton industry and is home to several small and medium-scale cotton production units. The village
            has a rich cultural heritage.
        </p>
    </font>
</body>

</html>

samusigapuram.html

<html>

<body bgcolor="lightblue">
    <font>
        <h1 align="center">samusigapuram</h1>
    </font>
    <font align="center" size="5">
        <p>
            <br>

            Agriculture: Like many villages in the Dindigul district, agriculture plays a vital role in the economy of
            Samusigapuram. Common crops grown include paddy, groundnut, cotton, and various vegetables. Farmers rely on
            both
            traditional and modern farming techniques.
            Cultural Practices: Villages like Samusigapuram observe traditional Tamil cultural practices, with festivals
            such as
            Pongal, Deepavali, and other regional celebrations being important aspects of life. Temples and religious
            rituals also
            hold a central place in the community.
            Community and Social Life: The village is likely to have a strong sense of community, where people maintain
            close
            relationships with one another and engage in shared activities, whether for religious, social, or
            agricultural purposes.
        </p>
    </font>
     
</body>

</html>
```




## OUTPUT
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (12).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
