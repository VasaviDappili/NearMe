# Ex04 Places Around Me
## Date: 22-03-2024

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
    <title>my city</title>
</head>
<body>
    <h1 align="center" bgcolor="Violet">NELLORE</h1>
    <h2 align="center" bgcolor="Violet">DAPPILI VASAVI(212223040030)</h2>
    <img src="Nellore.png.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Ayyappa Swamy Temple" title="Ayyappa Swamy Temple" href="Temple.html" coords="775,624,532,676" shape="rect">
    <area target="" alt="Nellore Nagara Vanam Park" title="Nellore Nagara Vanam Park" href="Park.html" coords="238,562,NaN" shape="circle">
    <area target="" alt="Sri Radhakrishna Swimming Pool" title="Sri Radhakrishna Swimming Pool" href="Swimming.html" coords="1216,136,1382,254" shape="rect">
    <area target="" alt="Hotel Southern Suites Nellore" title="Hotel Southern Suites Nellore" href="Hotel.html" coords="855,426,1036,504" shape="rect">
    <area target="" alt="Rainbow School" title="Rainbow School" href="School.html" coords="1100,764,1287,808" shape="rect">
</map>
</body>
</html>
<html>
<head>
<title>AYYAPPA SWAMI TEMPLE</title>
</head>
<body bgcolor="hotpink">
<h1 align="center"><b>NELLORE</b></h1>
<h2 align="center"><b>AYYAPPA SWAMI TEMPLE</b></h2>
<hr size="5" color="black">
<font face="Georgia" size="6">
<p align="center">
    It is one of the largest pilgrimage temple in the District with many devotees visiting every day. The temple is dedicated to a Hindu celibate deity Ayyappan also known as Dharma Shasta, who according to belief is the son of Shiva and Mohini, the feminine incarnation of Vishnu.
</p>
</body>
</html>
<html>
<head>
<title>NELLORE NAGARA VANAM PARK</title>
</head>
<body bgcolor="aquamarine">
<h1 align="center"><b>NELLORE</b></h1>
<h2 align="center"><b>NELLORE NAGARA VANAM PARK</b></h2>
<hr size="5" color="black">
<font face="Georgia" size="6">
<p align="center">
    Nellore Nagara Vanam Park, located at CV6V+R6F, Nellore, Andhra Pradesh 524345 in Kavali, andhra pradesh, is a located in India. Situated in a bustling area, the store is known for offering a diverse range of products and services to meet the varied needs of its customers. The strategic location in Kavali, a city in the state of andhra pradesh, makes it accessible and convenient for local residents and visitors. Nellore Nagara Vanam Park is committed to providing quality products and excellent customer service, making it a popular shopping destination in the region.
</p>
</body>
</html>
<html>
<head>
<title>SRI RADHAKRISHNA SWIMMING POOL</title>
</head>
<body bgcolor="cyan">
<h1 align="center"><b>NELLORE</b></h1>
<h2 align="center">SRI RADHAKRISHNA SWIMMING POOL<b></b></h2>
<hr size="5" color="black">
<font face="Georgia" size="6">
<p align="center">
`Radhakrishna swimming pool is renowned not only for exceptional pool design but also for that creates a welcoming atmosphere.Beyond a pool service,it's a hub of creativity and leisure fostering a community that values elegance and rejuvenation. 
</p>
</body>
</html>
<html>
<head>
<title>HOTEL SOUTHERN SUITES NELLORE</title>
</head>
<body bgcolor="TAN">
<h1 align="center"><b>NELLORE</b></h1>
<h2 align="center"><b>HOTEL SOUTHERN SUITES NELLORE</b></h2>
<hr size="5" color="black">
<font face="Georgia" size="6">
<p align="center">
Events like weddings, conferences, birthday celebrations, and exhibitions are handled in a spectacular manner at Hotel Southern Suites-Nellore. Weddings, receptions, social gatherings, and commercial endeavors can all be held at any of the hotels of the Hotel Southern Suites Group, which provides distinctive yet lovely venues. Our banquet halls, which are perfect for holding large festivities, are well-designed and structured, establishing the significance of our presence its spacious halls, Htel Southern Suites has hosted conferences and successful weddings. Let our banquet halls serve as the location where you say I do and start your life together. Hotel Southern Suites has you prepared for everything from decorations to catering! We provide on-site catering services that feature vegetarian and non-vegetarian options that honor regional and global flavors. Magnates and businesspeople are drawn to Hotel Southern Suites NELLOREs well-appointed accommodations. In addition to being situated in the NELLORE district, our hotels also provide boardrooms and conference spaces, which make it simpler for business travelers to arrange meetings without a hitch
</p>
</body>
</html>
<html>
<head>
<title>RAINBOW SCHOOL</title>
</head>
<body bgcolor="PINK">
<h1 align="center"><b>NELLORE</b></h1>
<h2 align="center"><b>RAINBOW SCHOOL</b></h2>
<hr size="5" color="black">
<font face="Georgia" size="6">
<p align="center">
    Rainbow School Nellore likely follows the curriculum prescribed by the educational authorities in India, which may include subjects such as Mathematics, Science, Social Studies, Languages (English, Hindi, and possibly a regional language), and additional subjects such as Computer Science, Physical Education,and Arts.Given the name "Rainbow School," it might prioritize creating an inclusive environment where diversity is celebrated. This could include fostering an atmosphere of respect and acceptance for students from various cultural, religious, and socioeconomic backgrounds.The school likely provides various facilities to support the learning and overall well-being of students, such as classrooms, libraries, laboratories, sports facilities, and outdoor spaces for recreation.
</p>
</body>
</html>
```
## OUTPUT
![alt text](<kavya/mapapp/static/Screenshot (25).png>)
![alt text](<kavya/mapapp/static/Screenshot (26).png>)
![alt text](<kavya/mapapp/static/Screenshot (27).png>)
![alt text](<kavya/mapapp/static/Screenshot (28).png>)
![alt text](<kavya/mapapp/static/Screenshot (29).png>)
![alt text](<kavya/mapapp/static/Screenshot (30).png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
