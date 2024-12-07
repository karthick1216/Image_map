# Ex04 Places Around Me
# Date:07/12/24
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map </title>
</head>
<body>
    <header>
        <h1>Interactive Image Map</h1>
    </header>
    
    <main>
        <p>Click on the different areas of the image to navigate to different pages:</p>
        <img src="image 01.png" alt="Image Map" usemap="#imagemap">
        <map name="imagemap">
            <area target="_blank" alt="New Zealand" title="New Zealand" href="land01.html" coords="436,342,542,385" shape="rect">
            <area target="_blank" alt="Chriatchurch" title="Chriatchurch" href="land02.html" coords="484,391,596,408" shape="rect">
            <area target="_blank" alt="Queenstown" title="Queenstown" href="land03.html" coords="354,458,450,479" shape="rect">
            <area target="" alt="Dunedin" title="Dunedin" href="land04.html" coords="410,496,488,518" shape="rect">
            <area target="" alt="Tasman Sea" title="Tasman Sea" href="sea01.html" coords="47,267,145,303" shape="rect">
            <area target="_blank" alt="Welligton" title="Welligton" href="land05.html" coords="558,284,654,316" shape="rect">
            <area target="_blank" alt="Hamilton" title="Hamilton" href="land06.html" coords="506,139,585,163" shape="rect">
            <area target="_blank" alt="Tauranga" title="Tauranga" href="land07.html" coords="604,135,686,156" shape="rect">
            <area target="_blank" alt="Aucland" title="Aucland" href="land08.html" coords="549,98,663,126" shape="rect">
            <area target="_blank" alt="Whangarei" title="Whangarei" href="land09.html" coords="529,51,634,73" shape="rect">
</map>
            
        </map>
    </main>

    <footer>
        <p>&copy; Karthick.S</p>
    </footer>
</body>
</html>
"""
land 01
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>New Zealand</h1>
    </header>
    <main>
        <img src="new.jpg" alt="A beautiful scenery">
        <p>New Zealand, a breathtaking island country located in the southwestern Pacific Ocean, is renowned for its diverse and stunning landscapes, ranging from lush green forests and rolling hills to dramatic fjords and pristine beaches. Comprising two main landmasses—the North Island and the South Island—and numerous smaller islands, New Zealand is a paradise for outdoor enthusiasts and nature lovers. Its vibrant culture blends Māori traditions with European influences, creating a unique and enriching cultural tapestry. The country is also famous for its friendly and welcoming people, often referred to as "Kiwis," who take pride in their rich heritage and progressive society. Whether you're exploring the geothermal wonders of Rotorua, hiking through the majestic Southern Alps, or experiencing the cosmopolitan charm of Auckland and Wellington, New Zealand offers an array of unforgettable experiences.</p>
 
    </main>

</body>
</html>
"""
"""
land 02
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Chriatchurch</h1>
    </header>
    <main>
        <img src="christchurch.jpeg" alt="A beautiful scenery">
        <p>Christchurch, the largest city in New Zealand's South Island, is known for its English heritage and resilience in the face of adversity. Nicknamed the "Garden City," Christchurch boasts an array of beautiful parks and gardens, including the expansive Hagley Park and the enchanting Christchurch Botanic Gardens. Despite being significantly impacted by a series of earthquakes in 2010 and 2011, the city has demonstrated remarkable recovery and transformation, with innovative architecture and vibrant cultural spaces emerging from the rebuild. Visitors can explore the bustling Riverside Market, take a punt ride on the Avon River, or admire the street art that adorns the city's walls. Christchurch serves as a gateway to the stunning landscapes of the Canterbury region, offering easy access to nearby beaches, alpine resorts, and adventure activities. The city's blend of natural beauty, cultural vibrancy, and spirit of innovation make it a compelling destination.</p>
    </main>
    
</body>
</html>
"""
"""
land 03
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Queenstown</h1>
    </header>
    <main>
        <img src="Queenstown.jpg" alt="A beautiful scenery">
        <p>Queenstown, often hailed as the adventure capital of New Zealand, is a vibrant and picturesque resort town nestled on the shores of Lake Wakatipu, surrounded by the dramatic Southern Alps. This stunning location in the Otago region offers a plethora of thrilling activities, making it a magnet for adrenaline seekers. From bungee jumping and skydiving to jet boating and paragliding, the options for adventure are seemingly endless. Beyond its exhilarating outdoor pursuits, Queenstown also boasts a lively arts and dining scene, with a variety of top-notch restaurants, cozy cafes, and galleries showcasing local talent. In the winter months, the town transforms into a hub for snow sports, drawing skiers and snowboarders to its world-class ski resorts like The Remarkables and Coronet Peak. Whether you're exploring the historic mining town of Arrowtown, cruising on the lake, or sampling the region's renowned Pinot Noir at a local winery, Queenstown promises an unforgettable experience in a breathtaking alpine setting.</p>
    </main>
   
</body>
</html>
"""
"""
land 04
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dunedin</h1>
    </header>
    <main>
        <img src="dunedin.jpg" alt="A beautiful scenery">
        <p>Dunedin, located on the southeast coast of New Zealand's South Island, is a city rich in history, culture, and natural beauty. Known for its well-preserved Victorian and Edwardian architecture, Dunedin offers a glimpse into the past with its charming streetscapes and historic buildings. The city is home to the prestigious University of Otago, New Zealand's oldest university, which brings a youthful vibrancy and academic atmosphere to the area. Dunedin's Scottish heritage is evident in its name and traditions, and it proudly celebrates this cultural connection. Nature enthusiasts will find plenty to explore, from the stunning coastal landscapes and wildlife of the Otago Peninsula to the lush forests and scenic trails nearby. Notably, the Otago Peninsula is renowned for its diverse wildlife, including albatrosses, seals, and penguins. With a thriving arts scene, diverse dining options, and a welcoming community, Dunedin is a city that seamlessly blends historical charm with modern vitality.</p>
    </main>
    
</body>
</html>
"""
"""
land 05
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welligton</h1>
    </header>
    <main>
        <img src="willington.jpg" alt="A beautiful scenery">
        <p>Wellington, the vibrant capital city of New Zealand, is renowned for its dynamic cultural scene, picturesque harbor, and stunning hilltop views. Nestled between rolling green hills and a sparkling blue harbor, Wellington offers a unique blend of natural beauty and urban sophistication. As the political heart of the country, it houses the iconic Beehive and New Zealand Parliament buildings. The city is also a hub of arts and creativity, featuring an array of theaters, museums, and galleries, including the renowned Museum of New Zealand Te Papa Tongarewa. Wellington’s culinary landscape is diverse and exciting, with numerous cafes, restaurants, and bars that reflect its cosmopolitan flair. The city's compact layout makes it easy to explore on foot, whether you're strolling along the bustling waterfront, hiking up to the Botanic Garden, or enjoying the panoramic views from Mount Victoria. With its blend of culture, history, and natural charm, Wellington captivates visitors and residents alike.</p>
    </main>
   
</body>
</html>
"""
"""
land 06
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hamilton</h1>
    </header>
    <main>
        <img src="hamilton.jpg" alt="A beautiful scenery">
        <p>Hamilton, located in the heart of New Zealand's North Island, is a bustling city known for its scenic beauty and vibrant community. Straddling the mighty Waikato River, Hamilton boasts lush parks, beautiful gardens, and a lively riverfront. The city is home to the renowned Hamilton Gardens, an award-winning attraction featuring themed gardens from around the world. Hamilton is also a center of education and innovation, with the University of Waikato driving academic and research excellence. The city's diverse culinary scene, lively arts and music festivals, and rich Māori heritage add to its cultural tapestry. Whether exploring the tranquil riverside trails, visiting the bustling farmers' markets, or enjoying the vibrant nightlife, Hamilton offers a dynamic blend of urban and natural experiences that captivate both residents and visitors alike.</p>
    </main>
   
</body>
</html>
"""
"""
land 07
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tauranga</h1>
    </header>
    <main>
        <img src="tauranga.jpg" alt="A beautiful scenery">
        <p>Tauranga, a vibrant coastal city located in New Zealand's Bay of Plenty region, is known for its stunning beaches, bustling port, and dynamic lifestyle. The city is one of the fastest-growing in the country, attracting both visitors and residents with its warm climate and outdoor recreational opportunities. Mount Maunganui, with its iconic volcanic cone, offers spectacular views and a popular beach that is perfect for surfing, swimming, and sunbathing. Tauranga's waterfront, lined with cafes, restaurants, and shops, is a lively area that reflects the city's energetic spirit. The city also has a rich cultural scene, with various festivals, art galleries, and cultural events throughout the year. Beyond its urban attractions, Tauranga is a gateway to numerous natural wonders, including lush orchards, thermal hot springs, and scenic hiking trails. With its blend of natural beauty, vibrant community, and economic growth, Tauranga is a city that beautifully balances the tranquility of nature with the excitement of urban life.</p>
    </main>

</body>
</html>
"""
"""
land 08
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Aucland</h1>
    </header>
    <main>
        <img src="ackland.webp" alt="A beautiful scenery">
        <p>Auckland, New Zealand's largest city, is a vibrant and bustling metropolis known for its stunning harbor, diverse population, and thriving cultural scene. Nicknamed the "City of Sails," Auckland boasts an impressive array of sailboats and yachts that adorn its harbors, reflecting the city's deep maritime heritage. The city's skyline is dominated by the iconic Sky Tower, which offers panoramic views of the surrounding area. Auckland's multicultural makeup contributes to its rich tapestry of food, festivals, and arts, making it a dynamic place to live and visit. Outdoor enthusiasts can enjoy the nearby beaches, volcanic cones, and lush parks, while urbanites can explore the trendy neighborhoods filled with cafes, restaurants, and shops. Auckland serves as a gateway to the rest of New Zealand, offering easy access to both natural wonders and urban delights. Whether you're strolling along the waterfront, visiting world-class museums, or hiking up a volcanic peak, Auckland's blend of natural beauty and urban sophistication is sure to captivate.</p>
    </main>
    
</body>
</html>
"""
"""
land 09
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Whangarei</h1>
    </header>
    <main>
        <img src="whang.jpg" alt="A beautiful scenery">
        <p>Whangarei, located in the northernmost region of New Zealand's North Island, is a charming city renowned for its natural beauty and vibrant local culture. Nestled along the picturesque Whangarei Harbour, this city offers stunning coastal vistas and a warm, welcoming atmosphere. Whangarei is a gateway to some of New Zealand's most beautiful beaches, lush native forests, and marine reserves, making it a haven for outdoor enthusiasts. Visitors can explore the Whangarei Heads, known for its dramatic landscapes and hiking trails, or take a trip to the breathtaking Poor Knights Islands, a world-famous dive spot. The city's vibrant arts scene is showcased in the Whangarei Art Museum and the bustling Town Basin, where art galleries, cafes, and shops create a lively waterfront atmosphere. Whangarei's rich Māori heritage and history are evident in its cultural sites and community events. Whether you're enjoying a leisurely stroll through the Quarry Gardens, taking in the scenic beauty of the Hatea River, or delving into the local culture, Whangarei offers a delightful blend of nature, history, and community spirit.</p>
    </main>
   
</body>
</html>
"""
"""
sea 01
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage with Image and Paragraph</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        img {
            width: 50%;
            height: auto;
            border-radius: 8px;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tasman Sea</h1>
    </header>
    <main>
        <img src="tasmansea.jpg" alt="A beautiful scenery">
        <p>The Tasman Sea, often referred to as the "Ditch" by locals, is a vast body of water that separates Australia and New Zealand. Covering an area of approximately 2,300,000 square kilometers, the Tasman Sea is renowned for its unpredictable weather and challenging navigational conditions. This dynamic sea has been a crucial route for maritime trade and exploration since the early days of European settlement. Rich in marine biodiversity, the Tasman Sea hosts a variety of sea life, including whales, dolphins, and numerous fish species. The coastline along the Tasman Sea is dotted with stunning beaches, dramatic cliffs, and vibrant coastal ecosystems. Famous coastal landmarks like Australia's Bondi Beach and New Zealand's Fiordland National Park are iconic features along its shores. Whether explored by adventurous sailors or admired from the land, the Tasman Sea remains a significant and awe-inspiring natural feature of the Australasian region.</p>
    </main>
    
</body>
</html>
"""
```
# OUTPUT

![Screenshot 2024-12-07 065947](https://github.com/user-attachments/assets/4f4b4017-adda-4a13-8184-a0824a7f69e1)
![Screenshot 2024-12-07 070014](https://github.com/user-attachments/assets/2be7f905-095f-4120-840d-00122665f7ac)
![Screenshot 2024-12-07 070036](https://github.com/user-attachments/assets/23b3cbd5-424d-4b9b-a18d-a73be37c2ae8)
![Screenshot 2024-12-07 070050](https://github.com/user-attachments/assets/930542a2-af5f-4df3-8002-df7eb3527c9f)
![Screenshot 2024-12-07 070106](https://github.com/user-attachments/assets/4a4f2a18-5993-451e-895d-39bf98d7a2b6)
![Screenshot 2024-12-07 070121](https://github.com/user-attachments/assets/2aa084cf-c6d2-4632-8325-0b7bdb4d5ca7)
![Screenshot 2024-12-07 070137](https://github.com/user-attachments/assets/308d1e55-fe1d-45f3-8e90-71eac31d46f6)
![Screenshot 2024-12-07 070156](https://github.com/user-attachments/assets/5496f559-002d-44de-bd68-047b0fc4b4a5)
![Screenshot 2024-12-07 070211](https://github.com/user-attachments/assets/5f0252b9-9930-4e7e-88d5-4525a2bd90a3)
![Screenshot 2024-12-07 070227](https://github.com/user-attachments/assets/dc8f65ee-9907-4f97-af2e-edd4e0bbcacd)
![Screenshot 2024-12-07 070252](https://github.com/user-attachments/assets/59249e4a-a109-4e57-80ec-f40fecca5a23)



# RESULT
The program for implementing image maps using HTML is executed successfully.
