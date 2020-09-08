# d3x_vehicleshop

## Requirements

Auto mode (everyone can buy vehicles from the dealer)

Mythic Notify -> https://github.com/JayMontana36/mythic_notify

## Download & Installation

- Import d3x_vehicleshop.sql into your database. 
- Images of cars must be added to the `HTML/imgs` directory 
- - All images must in .jpg format
- - Images must be named according to the `model` name in the database (if the car's model is **baller2** then name the jpg image to **baller2.jpg**)
- - All images included in this repository are 800px wide (which has been tested on a 1080 monitor and a 4k monitor and they looks fine) - this keeps the files size down - jpg is also used to reduce size as compression can be controlled reducing the download size for users. It may be possible to scale this down further. Though, the 147 imcluded images are only around 6MB.
- - [http://www.imagebatch.org/](http://www.imagebatch.org/) can be used to reformat and resize images  



- Add this in your server.cfg:
```start d3x_vehicleshop```
