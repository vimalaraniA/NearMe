# Ex04 Places Around Me
## Date: 13/10/2024

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
![Screenshot 2024-10-13 204822](https://github.com/user-attachments/assets/6e688009-91cf-469f-8b7f-77e59a4a3294)

![Screenshot 2024-10-13 204501](https://github.com/user-attachments/assets/d0b3f7e7-40c9-46bd-bcc4-a694c898e604)
![Screenshot 2024-10-13 204522](https://github.com/user-attachments/assets/1fdc333d-0251-43ec-bf51-34bbbe16ea63)
![Screenshot 2024-10-13 204556](https://github.com/user-attachments/assets/7a644ed3-8fdd-4f20-970b-a09ed2187844)
![Screenshot 2024-10-13 204610](https://github.com/user-attachments/assets/3b0a5dc6-873f-42a3-834e-9ba8f99bc7ec)
![Screenshot 2024-10-13 204631](https://github.com/user-attachments/assets/862d32ce-0c35-4402-aba8-dcbe0a8076e1)

## RESULT
The program for implementing image maps using HTML is executed successfully.
