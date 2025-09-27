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
        
        
        <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Vadapalani murugan temple" title="Vadapalani murugan temple" href="temple.html" coords="748,40,934,129" shape="rect">
    <area target="" alt="marina beach" title="marina beach" href="beach.html" coords="1547,104,89" shape="circle">
    <area target="" alt="Chennai international airport" title="Chennai international airport" href="airport.html" coords="257,600,426,729" shape="rect">
    <area target="" alt="Pheonix marketcity" title="Pheonix marketcity" href="marketcity.html" coords="719,637,914,710" shape="rect">
    <area target="" alt="ITC grand chola" title="ITC grand chola" href="hotel.html" coords="980,498,83" shape="circle">
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
        
    </body>
</html>




```

## OUTPUT
<img width="1906" height="1064" alt="map" src="https://github.com/user-attachments/assets/f0f24d2f-8633-4623-a2db-803bb9c44fc9" />
<img width="1904" height="1041" alt="hotel" src="https://github.com/user-attachments/assets/a531129c-8997-4016-b32d-c8d7dc994327" />
<img width="1906" height="1001" alt="temple" src="https://github.com/user-attachments/assets/49333101-a1e2-4021-a9a7-a6bc622cc217" />
<img width="1906" height="1032" alt="marketcity" src="https://github.com/user-attachments/assets/d49fc6b6-7138-4e4b-8c77-d31029523611" />
<img width="1906" height="1036" alt="airport" src="https://github.com/user-attachments/assets/f74aed9d-863c-46ef-8888-3ea5e910e4a2" />
<img width="1902" height="1036" alt="beach" src="https://github.com/user-attachments/assets/f462a5c8-aa4a-429e-ad7e-237fa15beddf" />




## RESULT
The program for implementing image maps using HTML is executed successfully.
