# Ex04 Places Around Me
##Date:20.11.23
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
<font color="red"><b>Thiruvannamalai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Divya P (23002600)</b></font>    
</h3>
<center>
<img src="map.png" usemap="#Mycity" height="680" width="1600">
<map name="MyCity">

    <area shape="rect" coords="700,250,850,400" href="home.html" tittle="My Home Town">
    <area shape="rect" coords="700,250,850,400" href="temple.html" tittle="Arunachalesvara Temple">
    <area shape="rect" coords="700,250,850,400" href="hospital.html" tittle="Government medical college hospital">
    <area shape="rect" coords="700,250,850,400" href="college.html" tittle="Shanmuga industries arts and science college">
    <area shape="rect" coords="700,250,850,400" href="hotel.html" tittle="Hotel comfort Inn">
</map>     
</center>
 </body>   
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Thiruvannamalai</b></font>
</h1>
<h2 align="center">
<font color="black"><b>My home town</b></font>
</h2>
<hr size="3" color="sky blue">
<p align="justify">
<font face="Georgia" size="5">
    A home, or domicile, is a space used as a permanent or semi-permanent residence for one or more human occupants, and sometimes various companion animals. It is a fully- or semi-sheltered space and can have both interior and exterior aspects to it.[vague] Homes provide sheltered spaces, for instance rooms, where domestic activity can be performed such as sleeping, preparing food, eating and hygiene as well as providing spaces for work and leisure such as remote working, studying and playing
</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Thiruvannamalai</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Arunachalesvara Temple</b></font>
</h2>
<hr size="3" color="orange">
<p align="justify">
<font face="Georgia" size="5">
    Arunachalesvara Temple (also called Annamalaiyar Temple) is a Hindu temple dedicated to the deity Shiva, located at the base of Arunachala hill in the town of Tiruvannamalai in Tamil Nadu, India. It is significant to the Hindu sect of Shaivism as one of the temples associated with the five elements, the Pancha Bhuta Sthalams, and specifically the element of fire, or Agni.

Shiva is worshipped as Arunachalesvara or Annamalaiyar, and is represented by the lingam, with his idol referred to as Agni lingam. His consort Parvati is depicted as Unnamalai Amman or Apithakucha Ambal.[2][3] The presiding deity is revered in the 7th-century Tamil Saiva canonical work, the Tevaram, written by Tamil saint poets known as the nayanars and classified as Paadal Petra Sthalam
</font>
</p>
</body>
</html>

hospital.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="Skyblue">
<h1 align="center">
<font color="red"><b>Thiruvannamalai</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Government medical college hospital</b></font>
</h2>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="5">
    The college emerged from the 1 April 2012 transfer of the 440-bed Tiruvannamalai Government District Headquarters Hospital (which had started as a government Taluk hospital in 1950) to the Department of Medical Education who then relaunched it as a teaching hospital offering 100 undergraduate places, the first of whom commenced studies in the 2013-2014 year
</font>
</p>
</body>
</html>    

college.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="violet">
<h1 align="center">
<font color="red"><b>Thiruvannamalai</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Shanmuga Industries arts and science college</b></font>
</h2>
<hr size="3" color="violet">
<p align="justify">
<font face="Georgia" size="5">
    Shanmuga Industries Arts and Science College, popularly known as SIASC, is a Co-educational institution promoted by Shanmuga Industries Educational Trust, Tiruvannamalai. The objective of the Trust is to enable the college into an institution of excellence and to let the rural youth living in and around Tiruvannamalai to have easy access to higher education. The college is situated in Tiruvannamalai on the Tiruvannamalai - Manalurpet state highway. The premier institute of college education was established in the year1996. Since its founding, SIASC has distinguished itself by providing a higher level of culture, cultivating good discipline and finer value of life among students. The college covers a vast area of land comprising classrooms, laboratories, computing centers, auditorium, hostel, library etc. SIASC has facilities that are exceptional in every way. The environment- friendly green campus and calm atmosphere at SIASC helps an individual to discover himself and the contribution he can make to the human kind
</font>
</p>
</body>
</html>

hotel.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lavendar">
<h1 align="center">
<font color="red"><b>Thiruvannamalai</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Hotel comfort Inn</b></font>
</h2>
<hr size="3" color="pink">
<p align="justify">
<font face="Georgia" size="5">
    Comfort Inn works on the Ideaof Indulgence with luxury attached to it. The property is always irresistible,an exclusive haven of solitude and luxury in the Tamilnadu's Temple city,offers travelers a new level of comfort with distinctive personal touch. The property commits towards providing theright blend of royal service, luxury and quiet efficiency.It's your perfect hotel destination for peaceful and convenient stay in the Tiruvannamalai! We provide a perfect atmosphere that suits both relaxation and business. We provide wide range of Standard & Deluxe rooms which includes 24 hours check in, checkout and Free Internet-WIFI
</font>
</p>
</body>
</html>

```


## OUTPUT
![Alt text](<Screenshot (24).png>)
![Alt text](<Screenshot (30).png>)
![Alt text](<Screenshot (29).png>)
![Alt text](<Screenshot (28).png>)
![Alt text](<Screenshot (26).png>)
![Alt text](<Screenshot (27).png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
