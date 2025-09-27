# Ex04 Places Around Me
## Name: HARI PRASATH E
## Ref No: 25007799
## Date: 21-09-2025

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
        <title>MAP</title>
    </head>

    <body bgcolor="cyan">
        <h1 align="center">CHENNAI -- HARI PRASATH E (25007799)</h1>
        <br>
        
        <img src="Screenshot.png" align="center" usemap="#image-map" title="My Fav Chennai">

<map name="image-map">
    <area target="" alt="CHENNAI INTERNATIONAL AIRPORT" title="CHENNAI INTERNATIONAL AIRPORT" href="airport.html" coords="150,623,395,685" shape="rect">
    <area target="" alt="MARINA  BEACH" title="MARINA  BEACH" href="beach.html" coords="1168,146,62" shape="circle">
    <area target="" alt="PHOENIX MARKET" title="PHOENIX MARKET" href="marketcity.html" coords="527,674,56" shape="circle">
    <area target="" alt="VADAPALANI MURUGAR KOVIL" title="VADAPALANI MURUGAR KOVIL" href="temple.html" coords="546,138,62" shape="circle">
    <area target="" alt="ITC GRAND CHOLA" title="ITC GRAND CHOLA" href="hotel.html" coords="595,470,819,519" shape="rect">
</map>
        


    </body>
</html>

airport.html
<html>
    <head>
        <title>AIRPORT</title>
    </head>
    <body bgcolor="deep blue">
        <h1 align="center">CHENNAI AIRPORT</h1>
        <p>
            <font size="5">Chennai International Airport is an international airport serving 
                the city of Chennai, the capital of Tamil Nadu, India. the airport is .. It is located in 
                Tirusulam in Chengalpattu district, in the Greater Chennai Metropolitan Area 
                around 21 km (13 mi) southwest of the city centre. The first air service was 
                operated in 1915 and the airport was commissioned in 1930. The airport 
                serves as the southern regional headquarters of the Airports Authority of 
                India (AAI) for South India comprising the states of Andhra Pradesh, 
                </font>
        </p>
        <img src="airport.png" width="700" height="400" title="Chennai Airport">
    </body>
</html>

beach.html
<html>
    <head>
        <title>BEACH</title>
    </head>
    <body bgcolor="light sand">
        <h1 align="center">MARINA BEACH</h1>
        <p>
            <font size="5">Marina Beach, or simply the Marina, is a natural urban beach in 
                Chennai, Tamil Nadu, India, along the Bay of Bengal. The beach runs from 
                near Fort St. George in the north to Foreshore Estate in the south, a 
                distance of 6.0 km (3.7 mi), making it the second longest urban beach in 
                the world. During summer months, about 15,000 to 20,000 
                people visit the beach daily.</font>
        </p>
        <img src="beach.png" width="700" height="400" title="Marina Beach">
    </body>
</html>


hotel.html
<html>
    <head>
        <title>HOTEL</title>
    </head>
    <body bgcolor="ivory">
        <h1 align="center">ITC GRAND CHOLA</h1>
        <p>
            <font size="5">The ITC Grand Chola is a 5-star luxury hotel in Chennai, India. 
                It is located in Guindy, opposite SPIC building and along the same row of 
                buildings as Ashok Leyland Towers. The building, designed by Singapore-based 
                SRSS Architects,  with a 30,000-sq ft pillar-less 
                ballroom. In Powai Lake (759 rooms) and Grand Hyatt 
                (694 rooms), both in Mumbai.</font>
        </p>
        <img src="ITC grand chola.png" width="700" height="400" title="ITC Grand Chola">
    </body>
</html>


marketcity.html

<html>
    <head>
        <title>MARKETCITY</title>
    </head>
    <body bgcolor="light beige">
        <h1 align="center">PHOENIX MARKETCITY</h1>
        <p>
            <font size="5">Phoenix Marketcity is a shopping mall developed by Phoenix Mills 
                Limited located in Chennai, Tamil Nadu, India. It was opened in January 2013 
                and is the 2nd largest mall in the city. It was the fourth largest mall in 
                India in 2018. It has a built up area of 1,000,000 square feet. Also there 
                is a . It is also located in the same compound of 
                Phoenix Marketcity Chennai.</font>
        </p>
        <img src="market.png" width="700" height="400" title="Phoenix Marketcity">
    </body>
</html>


temple.html
<html>
    <head>
        <title>TEMPLE</title>
    </head>
    <body bgcolor="gold">
        <h1 align="center">VADAPALANI MURUGAN TEMPLE</h1>
        <p>
            <font size="5">Vadapalani Andavar Temple is a Hindu temple dedicated to Lord Muruga. 
                It is located in Vadapalani, Chennai, Tamil Nadu, India. It was renovated in the 
                1920s and a Rajagopuram was built during that time. The temple has grown in 
                popularity, which is believed to be in part due to the patronage of cinema 
                stars.  in, and they believe in the power of this 
                sacred temple.</font>
        </p>
        <img src="temple.png" width="700" height="400" title="Vadapalani Temple">
    </body>
</html>



```

## OUTPUT
<img width="1082" height="715" alt="Screenshot 2025-09-27 132555" src="https://github.com/user-attachments/assets/71f5bd35-8f8e-4871-a524-5e4b6fc4b421" />
<img width="1078" height="473" alt="Screenshot 2025-09-27 132540" src="https://github.com/user-attachments/assets/c76846e9-0bba-4f34-bcf2-e9e2a20af953" />
<img width="1080" height="451" alt="Screenshot 2025-09-27 132608" src="https://github.com/user-attachments/assets/39962572-f624-4f8d-9349-e548844c55fb" />
<img width="1081" height="473" alt="Screenshot 2025-09-27 132620" src="https://github.com/user-attachments/assets/a934dd27-9b0c-41c4-afb5-48ddac4108cf" />
<img width="1087" height="468" alt="Screenshot 2025-09-27 132507" src="https://github.com/user-attachments/assets/b510c8ba-ab15-4580-9e2c-9cd83925a1c3" />




## RESULT
The program for implementing image maps using HTML is executed successfully.
