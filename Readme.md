# A Simple DIgital clock
## Using HTML CSS and Javascript

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

A digital clock  inspired by the graphical interfaces from Neon Genesis Evengelion.
It displays the time in hours, minutes and seconds.

- Installation
- HTML and CSS
- ✨Javascript

## Installation :)

- Download the latest version of the screensaver from the releases page.
- Extract zip file by doubble clicking on it
- Copy the main folder into the desired location
- Doubble click on the index.html file to open the digitcal clock


## HTML CODE :)
In this section, we have a dummy time in the format of “HH:MM:SS” wrapped inside a “div” 


![html](https://user-images.githubusercontent.com/95465072/175477133-54b5ffd4-8af1-48d2-a87d-96225aac7b17.png)




## CSS :)

For CSS, we have just aligned our clock to the center of the page. Other than that, it is just some font-size and width which you can adjust according to your need. 

![css](https://user-images.githubusercontent.com/95465072/175477251-f76e3e50-7afa-4f7a-82d8-0d864e0b7388.png)


## Javascript :)

###### For JavaScript, follow the below given steps.

- Step 1: Create a function “showTime”.
- Step 2: Create an instance of the Date object.
- Step 3: Using the methods of Date object get “hours”, “minute” and “seconds”.
- Step 4: Set AM/PM depending on the hour value. The Date object works on 24-hour format so we change hour back to 1 when it get’s larger than 12. The AM/PM also changes according to that.
- Step 5: Now make a string using the same HH:MM:SS format changing the hour, minute, and second value with the values, we get from Date object methods.
- Step 6: Now replace the string variable in the “div” using innerHTML property.
- Step 7: To call the function every second use setInterval() method and set time-interval as 1000ms which is equal to 1s.
- Step 8: Now call the function at the end to start function at exact reloading/rendering time as setInterval() will call first after 1s of rendering.





> **Note:** You can use digital fonts available online to make the clock look more beautiful. For that, you have to download their file into your project and then use the “font-face” property to use that custom font.
 

![javascript](https://user-images.githubusercontent.com/95465072/175477273-58cd7fcc-9a2c-475b-9ed1-a0752151c457.png)

