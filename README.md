# Ex03 Places Around Me
## Date: 28-11-2025

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
nithish_exp4.html

<html>
    <body>
        <h1 align="center" ><font color="red">Avadi-Paruthipattu</font></h1>
        <br><br>
        <h3 align="center"><font color="cyan">R. Nithish Aaditiyaa (25011876)</font></h3>
        <br>
        <img src="nearme.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Park" title="Park" href="Park.html" coords="1240,498,1444,577" shape="rect">
    <area target="" alt="CINEMAS" title="CINEMAS" href="CINEMAS.html" coords="175,108,169,136,319,146,319,102,236,103" shape="poly">
    <area target="" alt="Temple" title="Temple" href="Temple.html" coords="766,485,84" shape="circle">
    <area target="" alt="Bazaar" title="Bazaar" href="Bazaar.html" coords="1236,175,1339,195,1295,283,1142,256" shape="poly">
    <area target="" alt="GKS" title="GKS" href="GKS.html" coords="837,281,1056,326" shape="rect">
</map>
    </body>
</html>>

Bazaar.html

<html>
    <head>
        <h1 align="center"><font color="yellow">Avadi-Paruthipattu</font></h1>
    </head>
    <body bgcolor="green">
        <h4 align="center"><font color="brown">Ponnu Super Bazaar Avadi</font></h4>
        <hr>
        Super Bazaar boosts itself for its largest stocking of variety goods including, Provisions, Vegetables Fruits, (Gents / Ladies / Children -Readymade) Apparels, Consumer Durables, (Mixie, Grider etc) Electronic Goods (Plastic Items, Cookware, Artificial flowers, Gift Articles, Gift Coupons) Household Items etc.Every time during Festival seasons like Deepavali, Pongal, Ramzan, Christmas, New-year etc the shop is always swelled with people in more number than the regular days.The cordial staffs, Correct pricing, Wide variety has given them a special place in the heart of their customers.Ponnu Super Bazzar has become an iconic representation for its variety and correct pricing.
    </body>
</html>

CINEMAS

<html>
    <head>
        <h1 align="center"><font color="yellow">Avadi-Paruthipattu</font></h1>
    </head>
    <body bgcolor="violet">
        <h4 align="center"><font color="blue">VS CINEMAS</font></h4>
        <hr>
        VR Cinemas Pattabiram is located on the Tiruvallur High Road in Pattabiram, Chennai, Tamil Nadu 600072.The cinema distinguishes itself with premium audiovisual technology, specifically RGB 4K Laser projection and Dolby Atmos sound, aiming to offer an immersive experience. Generally, recent customer feedback is positive, frequently highlighting assets like the impressive large screen, ample parking facilities, and comfortable seating. However, a few older reviews have occasionally pointed out concerns regarding sound quality or the cleanliness of the washroom facilities.
    </body>
</html>

GKS.html

<html>
    <head>
        <h1 align="center"><font color="green">Avadi-Paruthipattu</font></h1>
    </head>
    <body bgcolor="blue">
        <h4 align="center"><font color="orange">GKS Convention Centre</font></h4>
        <hr>
        Located in the bustling area of Avadi, GKS Convention Centre is a renowned banquet hall in Chennai that offers luxurious modern rooms, suites, and impeccable catering services. It's a perfect blend of tradition and modernity, making it an ideal wedding venue.While the approach road may be cramped due to its location on Bazaar Road, once inside, guests are greeted with a spacious and extraordinary ambience. The team provides excellent support from booking to the end of the event
    </body>
</html>

Park.html

<html>
    <head>
        <h1 align="center"><font color="red">Avadi-Paruthipattu</font></h1>
    </head>
    <body bgcolor="pink">
        <h4 align="center"><font color="cyan">Avadi Paruthipattu Lake Green Park</font></h4>
        <hr>
        Paruthipattu Lake, also known as Avadi Lake, is a lake in Chennai, Tamil Nadu, India. It is located in the Avadi locality of Chennai. It is the second eco-park in the city after Chetput Lake.The lake remained one of the neglected waterbodies in the western suburbs for long, shrinking to 8 acres . In 2018, the Water Resources Department restored the lake at a cost of ₹ 280 million in two phases, developing it into an eco-tourism spot. The lake eco-park was opened to public on 21 June 2019. The renovation involved relocation of approximately 500 people
    </body>
</html>

Temple.html

<html>
    <head>
        <h1 align="center"><font color="pink">Avadi-Paruthipattu</font></h1>
    </head>
    <body bgcolor="red">
        <h4 align="center"><font color="yellow">Shiva Temple Jeeva Samadhi</font></h4>
        <hr>
        Several Shiva temples have a Jeeva Samadhi, which is the tomb of a saint or Siddhar who is believed to have attained spiritual liberation while still in a physical body. Examples include the Jeeva Samadhi of Mahan Gangadhara Navalar within his temple in Chennai, which includes a Shiva Lingam, and the Jeeva Samadhi of Bogar Siddhar within the Murugan Temple in Palani. Many of these temples have a central Shiva sanctum along with the Samadhi, sometimes marked by a Shiva Lingam or a Rishabam (bull) statue.
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (150).png>)
![alt text](<Screenshot (145)-1.png>)
![alt text](<Screenshot (146).png>)
![alt text](<Screenshot (147).png>)
![alt text](<Screenshot (148).png>)
![alt text](<Screenshot (149).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
