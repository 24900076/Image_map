# Ex04 Places Around Me
# Date:
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

    <html>
    <head>
      <title>My City</title>
    </head>
    <body>
      <h1 align="center">
        <font color="red"><b>Tambaram</b></font>
      </h1>

      <h3 align="center">
        <font color="blue"><b>Harshat</b></font>
      </h3>
    <center>
        <img src="map.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">
          <area shape="rect" coords="700,250,850,400" href="home.html" title="Home">
          <area shape="circle" coords="570,230,45" href="road.html" title="Muduchur road">
          <area shape="circle" coords="640,200,30" href="lake.html" title="Tambaram Lake">
          <area shape="circle" coords="1120,360,25" href="garden.html" title="GG Garden">
          <area shape="rect" coords="950,120,1100,140" href="stop.html" title="Pallikarani">
        </map>
      </center>
    </body>
    </html>

stop.html


    <html>
    <head>
      <title>Pallikarani</title>
    </head>
    <body bgcolor="blue">
      <h1 align="center">
        <font color="cyan"><b>Tambaram</b></font>
      </h1>
    <h3 align="center">
    <font color="lime"><b>Pallikarani</b></font>
  </h3>

  <hr size="3" color="cyan">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
        Pallikaranai is a rapidly developing residential locality in South Chennai,
        offering excellent connectivity to OMR, ECR, and GST Road. It is renowned 
        for the Pallikaranai Marsh, one of Chennai's last remaining natural wetlands, 
        which supports over 600 species of flora and fauna, including 176 bird species .​
      </p>
    </body
    </html>

# OUTPUT
# RESULT
The program for implementing image maps using HTML is executed successfully.
