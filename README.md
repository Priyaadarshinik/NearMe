# Ex04 Places Around Me
## Date: 25.3.24

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
        <h1 align="center"><b>MADURAI</b></h1>
        <h2 align="center"><b>PRIYAADARSHINI K (212223240126)</b></h2>
    <center>
        <img src="madu.png.png" usemap="#image-map" height="850" width="1800">
        <map name="image-map">
        <area target="" alt="Kamarajar University " title="Kamarajar University " href="university.html" coords="176,235,328,279" shape="rect">
        <area target="" alt="The Gateway hotel" title="The Gateway hotel" href="gateway.html" coords="747,477,913,522" shape="rect">
        <area target="" alt="Athisayam Theme Park" title="Athisayam Theme Park" href="themepark.html" coords="349,21,544,46" shape="rect">
        <area target="" alt="Radiance Cinema" title="Radiance Cinema" href="radiance.html" coords="798,16,969,45" shape="rect">
        <area target="" alt="Thirumalai Nayakkar Palace" title="Thirumalai Nayakkar Palace" href="palace.html" coords="1210,447,1359,489" shape="rect">
    </center>
</map>
</body>
</html>
```
```
themepark.html

<html>
    <head>
        <title>Athisayam Themepark</title>
    </head>
    <body bgcolor="brown">
        <h1 align="center"><b>MADURAI</b></h1>
        <h2 align="center"><b>ATHISAYAM THEME PARK </b></h2>
        <hr width="100%" size="4" color="white">
        <br>
        <h1 align="center">
            1) Athisayam is an amusement theme park located in Paravai on Madurai - Dindigul National Highway 7, 12 km from Madurai.<br>
            2) The park is located on a 70 acres (280,000 m2) site and features about 4 games and 2 water rides.</br>
            3) The park is popular for its water rides, recreating the experience of Courtalam waterfalls.<br>
        </br>
        </h1>
        </br>
    </body>
</html>
```
```
radiance.html

<html>
    <head>
        <title>Radiance</title>
    </head>
    <body bgcolor="grey">
        <h1 align="center"><b>MADURAI</b></h1>
        <h2 align="center"><b>RADIANCE CINEMA</b></h2>
        <hr width="100%" size="4" color="brown">
        <br>
        <h1 align="center">
            1) Radiance Cinema in Madurai is a gateway to a world of cinematic wonders.<br>
            2) Explore our five theme screens, each offering a unique and immersive movie-watching experience.</br>
            3) It is one of the biggest cinema theater in Madurai with distinct and diverse screens with great theme. <br>
        </br>
        </h1>
        </br>
    </body>
</html>
```
```
gateway.html

<html>
    <head>
        <title>The Hotel Gateway</title>
    </head>
    <body bgcolor="sky blue">
        <h1 align="center"><b>MADURAI</b></h1>
        <h2 align="center"><b>THE GATEWAY HOTEL</b></h2>
        <hr width="100%" size="4" color="brown">
        <br>
        <h2 align="center">
            1) Chennai may be the capital of Tamil Nadu but Madurai claims its soul and The Gateway Hotel Pasumalai, Madurai is located right at the heart of it.<br>
            2) A short distance from Madurai's IT corridor, The Gateway Hotel, Madurai sits at the top of the Pasumalai hill, surrounded by 62 acres of scenic gardens. </br>
            3) The 5 star hotel in Madurai serves a perfect vantage point to take in the picturesque views of the temple town and the Kodai hills.
        </br>4)  Garden Resort located atop Pasumalai Hill overlooking the Meenakshi Amman Temple. 
        </h2>
        </br>
    </body>
</html>
```
```
palace.html

<html>
    <head>
        <title>Thirumalai Nayakkar Mahal</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center"><b>MADURAI</b></h1>
        <h2 align="center"><b>THIRUMALAI NAYAKKAR MAHAL</b></h2>
        <hr width="100%" size="4" color="brown">
        <br>
        <h2 align="center">
            1) Thirumalai Nayak Palace is a 17th-century palace erected in 1636 by King Tirumala Nayaka, a king of Madurai's Nayaka dynasty who ruled Madurai from 1623 to 1659, in the city of Madurai, India. <br>
            2) The building, which can be seen today, was the main palace, in which the king lived.</br>
            3) The original palace complex was four times bigger than the present structure.<br>
            4) After independence, the Thirumalai Palace was declared as a national monument and is now under the protection of the Tamil Nadu Archaeological Department. 
        </br>5) In its heyday, the palace was considered to be one of the wonders of the South. The palace is located two kilometres (1.2 mi) south east of the Meenakshi Amman Temple.
        </h2>
        </br>
    </body>
</html>
```
```
university.html

<html>
    <head>
        <title>Kamarajar University</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center"><b>MADURAI</b></h1>
        <h2 align="center"><b>MADURAI KAMARAJAR UNIVERSITY</b></h2>
        <hr width="100%" size="4" color="brown">
        <br>
        <h2 align="center">
            1) Madurai Kamaraj University (MKU) is a public state university located in the Madurai city, in southern Tamil Nadu, India.<br>
            2) Madurai Kamaraj University offers 41 post graduate, 35 M.Phil. and 17 Diploma / P.G. Diploma / Certificate courses in the various departments. It was established in 1966.</br>
            3) MKU is one of the 15 universities in India with the University with Potential for Excellence status,which was awarded by the University Grants Commission (UGC) in India.
        </br>4) In 2021, the university was awarded an 'A++' grade from the National Assessment and Accreditation Council (NAAC) in its 4th cycle
        </h2>
        </br>
    </body>
</html>
```
## OUTPUT
![alt text](<coco/Screenshot 2024-04-01 145357.png>)
![alt text](<coco/Screenshot 2024-04-01 145412.png>)
![alt text](<coco/Screenshot 2024-04-01 145424.png>)
![alt text](<coco/Screenshot 2024-04-02 145216.png>)
![alt text](<coco/Screenshot 2024-04-01 145448.png>)
![alt text](<coco/Screenshot 2024-04-01 145502.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
