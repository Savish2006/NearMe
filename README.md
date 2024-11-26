# Ex04 Places Around Me
## Date: 26.11.2024

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
            <font color="red">RAMNAD</font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>SAVISH R [24900837]</b></font>
        </h3>
        <center>
            <img src="map2.png" usemap="#image-map">

            <map name="image-map">
            <area target="" alt="pasumbon nagar" title="pasumbon nagar" href="pasumbon nagar.html" coords="892,808,797,738" shape="rect">
            <area target="" alt="ramanathapuram palace" title="ramanathapuram palace" href="ramanathapuram palace.html" coords="385,449,628,507" shape="rect">
            <area target="" alt="azhalunachiyar temple" title="azhalunachiyar temple" href="azhalunachiyar temple.html" coords="590,345,791,393" shape="rect">
            <area target="" alt="yafa mahal" title="yafa mahal" href="yafa mahal.html" coords="828,510,661,463" shape="rect">
            <area target="" alt="suntharalinganar" title="suntharalinganar" href="suntharalinganar.html" coords="1122,155,921,129" shape="rect">
        </map>       
        </center>
    </body>
</html>

azhalunachiyar temple.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="yellow">
    <h1 align="center">AZHAGUNACHIYAR TEMPLE</h1>
    <p>The Azhagunachiyar Temple, located in Ramanathapuram district, is a revered shrine dedicated to Goddess Azhagunachiyar, an incarnation of Goddess Lakshmi. Known for its spiritual significance and architectural beauty, the temple is an integral part of the region's cultural heritage. The sanctum sanctorum houses the idol of Azhagunachiyar, adorned with intricate ornaments, symbolizing grace and prosperity. Devotees visit the temple to seek blessings for happiness, wealth, and well-being. The temple’s festivals, celebrated with grandeur, attract pilgrims from far and wide, creating a vibrant atmosphere filled with rituals, music, and devotion. Surrounded by serene landscapes, the temple offers a tranquil environment for prayer and meditation. Its intricate carvings and traditional design reflect the craftsmanship of ancient Tamil architecture, making it a spiritual and architectural treasure. Azhagunachiyar Temple stands as a beacon of faith, embodying the rich traditions and devotion of Tamil Nadu.</p>
</body>
</html>

pasupon nagar.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="red">
    <h1 align="center">PASUPON NAGAR</h1>
    <p>Pasupon Nagar is a vibrant and well-established residential locality, known for its serene atmosphere and community-oriented living. The area offers a mix of independent houses and modern apartments, catering to families and individuals alike. It boasts excellent connectivity to nearby urban centers through public transportation, making it convenient for daily commutes. Residents have access to essential amenities, including schools, healthcare facilities, supermarkets, and recreational parks, ensuring a comfortable lifestyle. Cultural landmarks such as temples or community centers often add a traditional charm to the neighborhood, fostering a sense of heritage and belonging. With its lush greenery and peaceful environment, Pasupon Nagar provides a perfect balance between urban convenience and suburban tranquility. The diverse and inclusive community further enhances its appeal, making it a sought-after place to live</p>
</body>
</html>

ramanathapuram palace.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="green">
    <h1 align="center">RAMANATHAPURAM PALACE</h1>
    <p>The Ramanathapuram Palace, also known as the Ramnad Palace, is a historical gem that reflects the grandeur and cultural heritage of the Sethupathi dynasty. Located in the heart of Ramanathapuram, Tamil Nadu, the palace stands as a testament to the architectural brilliance of its time, blending Dravidian and Mughal influences. Its expansive halls, intricate carvings, and antique furnishings narrate the stories of the region's royal past. The palace once served as the residence of the rulers of the Sethupathi kingdom, who played a pivotal role in protecting and promoting the traditions of the region. Today, it remains a major tourist attraction, drawing visitors with its regal charm and historical significance. The site also houses a museum showcasing artifacts, paintings, and memorabilia from the Sethupathi era, providing a glimpse into their rich legacy. The Ramanathapuram Palace is not only a monument of architectural splendor but also a cultural landmark that continues to inspire awe and admiration. </p>
</body>
</html>

suntharalinganar.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="pink">
    <h1 align="center">SUNTHARALINGANAR</h1>
    <p>
        Sundaralinganar in Ramnad (Ramanathapuram) is a celebrated figure known for his significant contributions to Tamil literature and social reform. Born in a region steeped in culture and history, he emerged as a passionate advocate for Tamil identity, language, and heritage. Sundaralinganar's works reflect his deep understanding of Tamil literature and his commitment to uplifting society through education and progressive ideals. He played a vital role in promoting social justice and equality, aligning himself with movements aimed at eradicating caste discrimination and empowering marginalized communities. His legacy is commemorated in Ramnad through various initiatives and institutions named in his honor, serving as a reminder of his impactful life and enduring contributions. Sundaralinganar remains an inspiration, celebrated for his dedication to cultural preservation and social harmony. 
    </p>
</body>
</html>


yafa mahal.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="cyan">
    <h1 align="center">YAFA MAHAL</h1>
    <p>Yafa Mahal in Ramnad (Ramanathapuram) is a prominent landmark known for its architectural elegance and cultural significance. Situated in the heart of the city, this majestic structure blends traditional and modern design elements, making it a visual treat for visitors and locals alike. Yafa Mahal often serves as a venue for grand celebrations, including weddings, social gatherings, and cultural events, owing to its spacious interiors and well-maintained facilities. Surrounded by the historical and scenic charm of Ramnad, it offers a glimpse into the region's rich heritage while catering to contemporary needs. The venue is easily accessible, with good connectivity to other parts of the city, and is highly regarded for its ambiance and hospitality. Yafa Mahal stands as a symbol of elegance and tradition, making it a cherished part of Ramnad's cultural landscape.</p>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (47).png>)
![alt text](<Screenshot (48).png>)
![alt text](<Screenshot (49).png>)
![alt text](<Screenshot (50).png>)
![alt text](<Screenshot (51).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
