# Ex04 Places Around Me
## Date: 20.09.2025

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
        <title>Map View</title>
    </head>
<body bgcolor="lightgreen">
<center>
<h1>Map View</h1>
<h1>THANGAPAZHAM(25017581)</h1>

<br>
<img src="Screenshot (36).png" usemap="#image-map" >
<br>
<h1>Click the temple which you want to know</h1>
</center>

<map name="image-map">
    <area target="" alt="kailasanathar" title="kailasanathar" href="kailasanathar.html" coords="387,266,111,358" shape="rect">
    <area target="" alt="kamakshiamman" title="kamakshi amman" href="kamakshiamman.html" coords="945,347,695,442" shape="rect">
    <area target="" alt="viswanathar" title="viswanathar" href="viswanathar.html" coords="457,165,104" shape="circle">
    <area target="" alt="perumal" title="perumal" href="perumal.html" coords="1113,471,1289,467,1369,547,1137,545" shape="poly">
    <area target="" alt="ekambaranadhar" title="ekambaranadhar" href="ekambaranadhar.html" coords="801,158,104" shape="circle">
</map>
</body>
</html>

ekambaranadhar.html

<html>
<head>
    <title>Ekambaranadhar Temple</title>
</head>
<body bgcolor="lightblue">
    <center>
    <h1>Ekambaranadhar Temple</h1>
    <hr>
    <p>
        Ekambareswarar Temple (Ekambaranathar Temple) (Kacchi Eakamban Tirukkoyil) is a Hindu temple dedicated to the god Shiva, located in the town of Kanchipuram in Tamil Nadu, India. 
        It is significant to the Hindu sect of Saivism as one of the temples associated with the five elements, the Pancha Bhoota Stalas, 
        and specifically the element of earth, or Prithvi. Shiva is worshiped as Ekambareswarar or Ekambaranathar or Rajlingeswaram, and is represented by the lingam as Prithvi lingam. 
        His consort Parvati is depicted as Elavarkuzhali.
    </p>

    </center>
</body>
</html>

kailasanathar.html

<html>
<head>
    <title>Kailasanathar Temple</title>
</head>
<body bgcolor="lavander">
    <center>
    <h1>Kailasanathar Temple</h1>
    <hr>
    <p>
        Temple construction is credited to the Pallava dynasty, who had established their kingdom with Kanchipuram (also known as "Kanchi" or "Shiva Vishnu Kanchi") as the capital city, 
        considered one of the seven sacred cities under Hinduism. In Kanchi, after the Pallavas expanded their territories to the north, west and south both within Tamil, 
        Andhra and Kannada territories under Emperor Narasimhavarman I, they started expanding their capital city of Kanchipuram and built many temples of great magnificence. 
        Among the two unique specimens of temple architecture of the period 640–730 CE are the Tiru Parameswara Vinnagaram, which is also known as the Vaikunta Perumal temple and the Kailasanathar Temple.
    </p>

    </center>
</body>
</html>

kamakshiamman.html

<html>
<head>
    <title>Kamakshi Amman Temple</title>
</head>
<body bgcolor="orange">
    <center>
    <h1>Kamakshi Amman Temple</h1>
    <hr>
    <p>
        Sri Kamakshi Amman Temple, along with the goddesses Meenakshi at Madurai, Neelayadakshi of Nagapattinam and either Vishalakshi at Varanasi or Akhilandeshwari at Thiruvanaikovil, 
        is one of the most important centers of Shaktism in the state of Tamil Nadu. The Sri Kamakshi Amman Temple is dedicated to the goddess Kamakshi, one of the form of Parvati and the highest aspect of Adi Parashakti, 
        she is the mighty goddess in Shaktism. Kamakshi is praised as 'Sri Mata' (respected mother) as the first name in the Lalitha Sahasranama. This temple is also one of the 18 main Shakti Pithas.
    </p>

    </center>
</body>
</html>

perumal.html

<html>
<head>
    <title>Perumal Temple</title>
</head>
<body bgcolor="yellow">
    <center>
    <h1>Perumal Temple</h1>
    <hr>
    <p>Thiru Parameswara Vinnagaram or Vaikunta Perumal Temple is a Hindu temple dedicated to the God Vishnu, located in Kanchipuram in the Southern Indian state  of Tamil Nadu.
       Constructed in the Dravidian style of architecture, the temple is glorified in the Nalayira Divya Prabandham, the early medieval Tamil canon of the Alvar saints from the 6th through the 9th centuries CE.
       It is one among the 108 Divya Desams dedicated to the God Vishnu, who is worshipped as Vaikuntanathan (lit. 'Lord of Vaikunta') and his consort, the Goddess Lakshmi as Sri Vaikundavalli. 
       The temple is considered the second oldest extant temple in Kanchipuram after the Kailasanathar temple.
    </p>

    </center>
</body>
</html>

viswanathar.html

<html>
<head>
    <title>Viswanathar Temple</title>
</head>
<body bgcolor="pink">
    <center>
    <h1>Viswanathar Temple</h1>
    <hr>
    <p>
        Some of the salient features of this temple are...
        The temple faces east with an entrance arch. Balipeedam and Rishabam, Vinayagar, and Sri Valli Devasena Subramaniar are in the center of Muthi / Mukthi Mandapam. 
        Moolavar is in the Sanctum Sanctorum facing east. A Pallava period icon of Somaskandar is on the back wall of the sanctum sanctorum. 
        There are 9 bas reliefs on the south side wall, 5 bas reliefs on the west side wall, and 3 bas are on the north side wall. 
        Mahishasuramardini, Maha Vishnu, Vinayagar, Murugan, Dakshinamurthy, Chandikeswarar, and Bhairavar are also there.
    </p>

    </center>
</body>
</html>

```
## OUTPUT
![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
