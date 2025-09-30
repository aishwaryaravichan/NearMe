# Ex04 Places Around Me
## Date:30.09.2025 

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
home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body align="center">
<img src="Screenshot 2025-09-30 110823.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="madurai airport" title="madurai airport" href="airport.html" coords="472,582,720,702" shape="rect">
    <area target="" alt="malai Kovil" title="malai Kovil" href="temple.html" coords="1124,357,127" shape="circle">
    <area target="" alt="PTR college" title="PTR college" href="college.html" coords="64,481,362,385,301,597" shape="poly">
</map>
</body>
</html>

airport.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="airport.png">
</body>
</html>

college.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="college.png">
</body>
</html>

college.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="temple.png">
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-09-30 113632.png>)
![alt text](<Screenshot 2025-09-30 113647.png>)
![alt text](<Screenshot 2025-09-30 113700.png>)
![alt text](<Screenshot 2025-09-30 113719.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
