### Making_life_easy
Collection of personal projects aiming towards saving time. 

# 1.1 To convert screen-shots or other images to a pdf.
-Inspired by Virtual semseter

It's tough when professors don't share notes and slides just after the class and you wish to share the screenshots taken in class with your friends.

# 2.1 Creating Shape-Files from Lat_Long
Initially I used "Geocode" plugin on Google-Sheets to fetch Lattitude and Longitude points for exact address. I could have have used Web-Scrapping but this is was way more comfortable.
After getting the lat-long, we need to create shapes/ polygon/ buffer areas. Finally after creating the polygons, we need to save it as a shapefile and later this can be used on Google Earth Engine Code. Caution: shape-files only understand [0-9, a-z, A-Z, some special charaters] but not every native script.
