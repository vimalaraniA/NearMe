# Ex04 Places Around Me
## Date: 29/03/2024

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
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>RANIPET</b></font>
</h1>
<center>
<img src="Screenshot 2024-03-27 192646.png" usemap="#image-map" height="610" width="1450">
<map name="#MyCity">
<map name="image-map">
    <area target="" alt="VIT" title="VIT" href="vit.html" coords="187,315,60,201" shape="rect">
    <map name="image-map">
        <area target="" alt="walajapet" title="Walajapet" href="walajapet.html" coords="797,312,1000,389" shape="rect">
        <map name="image-map">
            <area target="" alt="Ranipet" title="Ranipet" href="ranipet.html" coords="769,250,1010,394" shape="rect">
            <map name="image-map">
                <area target="" alt="Ammoor" title="Ammoor" href="ammoor.html" coords="985,300,1170,180" shape="rect">
                 <map name="image-map">
                    <area target="" alt="Arcot" title="Arcot" href="arcot.html" coords="674,410,887,488" shape="rect">
                </map>
                </map>
            </map>
        </map>
    </map>
</map>
</map>
</center>
</body>
</html> 
```


## OUTPUT
![alt text](<Screenshot 2024-03-29 084458-1.png>)
![alt text](<Screenshot 2024-03-29 092924.png>)
![alt text](<Screenshot 2024-03-29 093001.png>)
![alt text](<Screenshot 2024-03-29 092934.png>)
![alt text](<Screenshot 2024-03-29 093019.png>)
![alt text](<Screenshot 2024-03-29 092948.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
