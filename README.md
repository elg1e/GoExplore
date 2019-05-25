# GoExplore

 GoExplore is a project created to allow users to discover and prepare for trips across the globe. 
GoExplore allows users to search for a destination then find bars, resturants, accommodation and cafes within that area. 
 
## UX

 The idea for this project was to create a website for users to be able to orginise their trips with one single search. 
The priority for this project was to ensure the site is as user friendly as possible. By simply typing a destination and searching the user can find out about accommodation, bars, cafes and resturants. 

User Stories:

- As a user I want to be able to search for a city so that I can find out more information about it.
- As a user I want to be able to press a button so that I can see the cafes/accommodation/bars/restaurants in the city I'd like to visit.
- As a user I want to be able to press a button to guide me through the steps so that I understand how to use the website.
- As a user I want to be able to click a link to a cafe/hotel/bar/restaurant so that I can find out more information about it.

## Features

### Google Map

 The main feature of this website is the [Google Maps API](https://cloud.google.com/maps-platform/). This allows the users to view anywhere around the world. This is how the user will be able to find a destination, use one of four filter buttons which will places markers on the map and allow the user to research the area before travelling. 

### Help Box

 Another fuction added to the site is a help button. This help button can be pressed at anytime by the user if they do not understand how to use the site. When the help button is pressed a pop up box will appear. In this box is a step by step guide on how to use the site.
 
#### Features left to implement

 Another feature I would like to implement in the future would be more filters to the map to allow users to find even more information about the places they are looking to visit.
 
## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML): Mark-up language used for creating the website.
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets): Stylesheet language used to create the presentation of the website.
- [JavaScript](https://www.javascript.com/): Primary function of the site for all user interaction.
- [JQuery](https://jquery.com/): Used to simplify some of the DOM manipulations.
- [BootStrap](https://getbootstrap.com/): Used to create the layout of the webpages.
- [GoogleFonts](https://fonts.google.com/): Used to add different fonts to the website.

## Testing

Manual Testing was complete to prove that the functionality of the website is working correctly. The reason I have chosen to use manual testing instead of automated test is due to the JavaScript used in this website is from the Google Map API. 

#### Search Bar Test

1. Click the search bar in the center of the screen.
2. Type a city/town (The search bar will autocomplete city/town). 
3. Press Enter to find the city/town. 
4. Google Maps API finds the city.
5. Repeat test from the beginning. 
6. Click the search bar in the center of the screen.
7. Type anything else other than a city/town i.e. a country or state (The search bar will not autocomplete).

#### Marker Test

1. Press the search bar in the center of the screen.
2. Type a city/town (The search bar will autocomplete city/town). 
3. Press Enter (This will tell the Google API to search the location and move to it). 
4. Google Maps API finds the city.
5. Click the restaurant button (This will tell the Google API to place markers on the restaurants in the area).
6. Markers will appear on the screen to show restaurants.
7. Click markers to show restaurants (Infomation Windows will appear for each marker).
8. Click reset button to remove the markers and reset the map bounds back to it's original position.
9. Repeat this method for each individual button (Restaurants/Accommodation/Cafes/Bars).

#### Help Button 

1. Click the help button on the top right of the screen.
2. A new window will appear showing a guide for the website. 
3. Click the X in the top corner of the new window to close the page.

### Responsive design
The website has been tested using the developer tools in the browser so that the website will be compatible in different screen sizes. When the site is used on a small screen size the site is designed to stay as simple and clutterless as possible.

The website has been tested in the following device resolutions:

#### Mobiles

- Pixel 2/XL
- iPhone 5/SE/6/7/8
- iPhone 6/7/8+
- iPhone X
- Galaxy S5/S9/S9+

#### Tablets

- iPad/iPad Pro
- Kindle Fire HDX

#### Desktops/XL Desktops

The website has been tested with these browsers:

- Google Chrome
- FireFox
- Internet Explorer

### Validation

The website has be validated using: 

- [HTML Validator](https://validator.w3.org/nu/#textarea) Showing no errors.
- [CSS Validator](https://jigsaw.w3.org/css-validator/validator) Showing no errors.
- [JavaScript Validator]() Showing no errors.

## Deployment

To create the website, I have used the coding platform [Cloud9](www.cloud9.io). Deployment and source control was entirely done via [GitHub](www.github.com). My repository can be found here:

https://elg1e.github.io/GoExplore/

I've published the source code built from the master branch using GitHub Pages. The live site can be found here:

https://elg1e.github.io/GoExplore/

## Credits

### Content

The Google Maps was taken from: https://cloud.google.com/maps-platform/

### Media

The image used for the site were taken from:

- [1zoom](http://s1.1zoom.me/b4853/62/Canada_Houses_Marinas_Evening_Bridges_Vancouver_521398_1920x1080.jpg)