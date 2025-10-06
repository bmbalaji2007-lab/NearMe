# Ex04 Places Around Me
## Date: 06-10-2025
## Name: B M BALAJI
## Ref No: 25016669

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
        <h1 align="center">CHENNAI -- B M BALAJI (25016669)</h1>
        <br>
        
        <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="phoenix Market city" title="phoenix Market city" href="maket.html" coords="712,642,923,703" shape="rect">
    <area target="" alt="Chennai International Airport" title="Chennai International Airport" href="airport.html" coords="381,663,68" shape="circle">
    <area target="" alt="Vadapalani temple" title="Vadapalani temple" href="temple.html" coords="853,124,109" shape="circle">
    <area target="" alt="ITC grand chola" title="ITC grand chola" href="hotel.html" coords="745,462,936,533" shape="rect">
    <area target="" alt="Marina Beach" title="Marina Beach" href="beach.html" coords="1540,119,70" shape="circle">
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
<img width="1920" height="1080" alt="map (2)" src="https://github.com/user-attachments/assets/6f401c00-18a3-4d7c-9a47-ddccd37047df" />
<img width="1920" height="1080" alt="temple" src="https://github.com/user-attachments/assets/334b5442-3ed9-460b-9048-73ce5400fddd" />
<img width="1920" height="1080" alt="itc" src="https://github.com/user-attachments/assets/e58720b3-7d8e-44be-bd15-59924305ef39" />
<img width="1920" height="1080" alt="airport" src="https://github.com/user-attachments/assets/a3b2ec3c-42b3-4e9b-9173-fc4c74802617" />
<img width="1920" height="1080" alt="beach" src="https://github.com/user-attachments/assets/877de058-aeef-4fc3-a6b8-29d373e679a7" />







## RESULT
The program for implementing image maps using HTML is executed successfully.
