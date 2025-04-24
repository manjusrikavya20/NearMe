# Ex04 Places Around Me
## Date: 24/04/2025

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
        <h1 align="center">
            <font color="red"><b>ARIYALUR</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>AKASH P(212224220006)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="MADURAI VEERAN KOVIL" title="MADURAI VEERAN KOVIL" href="verrankovil.html" coords="39,226,269,260" shape="rect">
                <area target="" alt="HOTEL" title="HOTEL" href="hotel.html" coords="965,526,1235,575" shape="rect">
                <area target="" alt="MURUGAN TEMPLE" title="MURUGAN TEMPLE" href="murugantemple.html" coords="1397,529,1653,659" shape="rect">
                <area target="" alt="KANNAPAR TEMPLE" title="KANNAPAR TEMPLE" href="kannapartemple.html" coords="576,449,811,562" shape="rect">
                <area target="" alt="ARIYALUR" title="ARIYALUR" href="ariyalur.html" coords="838,378,1055,447" shape="rect">
            </map>
        </center>  
    </body>
</html>

kannartemple.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>ARIYALUR</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>GANGAIKONDA CHOLAPURAM</b></font>
        </h2>
        <br>
        <hr size="3" color="yellow">
        <br>
        <center><img src="G.avif" alt="" height="400" width="600">
        <img src="g2.webp" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                The centerpiece of Gangaikonda Cholapuram is the Brihadisvara Temple, a UNESCO World Heritage Site and a masterpiece of Chola architecture. Commissioned by King Rajendra Chola I in 1035 CE, the temple was built to commemorate his victorious expedition to the Ganges River, symbolizing the Chola dynasty's imperial power. ​   
              
                
            </font>
        </p>
    </body>
</html>

ariyalur.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>ARIYALUR</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>ARIYALUR</b></font>
        </h2>
        <br>
        <hr size="3" color="yellow">
        <br>
        <center><img src="home.jpg" alt="">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Ariyalur is a historically rich and geologically significant town located in the state of Tamil Nadu, India. Known for its ancient temples and cultural heritage, the region was once ruled by the Cholas, Pallavas, Nayaks, and later the British. One of its most remarkable features is its unique geology—Ariyalur is famous for its limestone deposits and ancient fossils, including those from the Cretaceous period, making it a treasure trove for geologists and paleontologists. The local economy thrives on cement industries due to the abundance of limestone, alongside agriculture, with crops like paddy, sugarcane, and groundnut being commonly grown. 
                </font>
                </p>
    </body>
</html>

veerankovil.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>ARIYALUR</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>VEERAN KOVIL</b></font>
        </h2>
        <br>
        <hr size="3" color="yellow">
        <br>
        <center><img src="veeran.webp" alt="" height="400" width="600">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Located in Thirumazhapadi, this temple is dedicated to Lord Shiva, known here as Vaidyanathaswamy. His consort, Parvati, is revered as Sundarambikai. The temple holds historical significance and is a site of major religious importance. 
                
            </font>
        </p>
    </body>
</html>

hotel.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>ARIYALUR</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>HOTEL KARNAS</b></font>
        </h2>
        <br>
        <hr size="3" color="yellow">
        <br>
        <center><img src="hotel.avif" alt="" height="400" width="600">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Known for its comfortable rooms and vegetarian cuisine. Offers basic amenities and is conveniently located near the railway station.A budget-friendly option with essential facilities.
            </font>
        </p>
    </body>
</html>

murugantemple.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>ARIYALUR</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>MURUGAN TEMPLE</b></font>
        </h2>
        <br>
        <hr size="3" color="yellow">
        <br>
        <center><img src="murugan.jpg" alt="" height="400" width="600">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                In Ariyalur district, Tamil Nadu, devotees of Lord Murugan can visit the Murugan Temple located in Valajanagaram, near Hasthinapuram. The temple's address is 448G+Q33, Hasthinapuram, Valajanagaram, Tamil Nadu 621704, India. While specific details about this temple's history and architecture are limited, it serves as a local place of worship for Murugan devotees in the region
            </font>
        </p>
    </body>
</html>
```

## OUTPUT

![image](https://github.com/user-attachments/assets/c8919ef3-bff6-45c2-93e9-528012781f03)

![image](https://github.com/user-attachments/assets/03958a43-5ee4-4103-9b45-cee9d2aa01f1)

![image](https://github.com/user-attachments/assets/0a3f078c-4d5e-4a63-bbe9-8ecdff72d06a)

![image](https://github.com/user-attachments/assets/202a3c35-bb7e-419d-9fba-da5d03350e7b)

![image](https://github.com/user-attachments/assets/0539c16c-d295-4491-b5ae-2ef00f208b0a)

![image](https://github.com/user-attachments/assets/b338e38a-4e95-4f9f-9f63-412ca4e4b3b6)


## RESULT
The program for implementing image maps using HTML is executed successfully.
