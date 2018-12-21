# Entertain Me

The purpose of this project is to make an accessible and easy to use application that displays events of a variety of categories when supplied with a specified date and location.

## How To

* Entertain Me's user interface is very straight forward. Initially the user will be presented with three input fields; location, date, and category, followed by a Search button.

![Entertain Me](https://user-images.githubusercontent.com/40774762/50363436-69955f00-0520-11e9-9073-04c39c0832c9.png)

* The location field will take locations in a variety of formats. Acceptable formats include: "City", "City, State", "City, State, Country", and 5-digit postal codes. The location field has autocomplete functionality. This field is required.

<p align="center">
  <img src="https://user-images.githubusercontent.com/40774762/50363534-ef190f00-0520-11e9-8d6e-a893552e974e.png" alt="auto-fill"/>
</p>

* The date field accepts any dates that are not before the current date. Manually entered dates must be formatted as MM/DD/YYYY. There is also a built in calender view that can be accessed by clicking the calander icon next to the date field. This field is required.

![calendar](https://user-images.githubusercontent.com/40774762/50363760-f68ce800-0521-11e9-86ab-0f7e727a2ca8.png)

* The catagory field is a drop down menu that offers several event catagories. This field is optional.

<p align="center">
  <img src="https://user-images.githubusercontent.com/40774762/50363830-4c619000-0522-11e9-9ad7-227e13e71600.png" alt="categories"/>
</p>

* With valid inputs for the location and date fields, clicking the "Search" button will load a number of cards, each displaying unique events. 
* The cards consist of an image pertaining to the event, the title of the event, and a Google Maps button. 
* Clicking the card will display information about the event.
* Clicking the Google Maps button will display a modal that can be used to get directions to the event's venue.

## Technologies Used

Eventful Api: http://api.eventful.com/

Google Maps Api: https://cloud.google.com/maps-platform/

Materialize: https://materializecss.com/

Algolia Places: https://community.algolia.com/places/

## Contributors

Jover Lee: https://github.com/joverlee521

Ethan Fisher: https://github.com/EthanPFisher

Simin Shamsfallah: https://github.com/siminshams

Rudy Sharar: https://github.com/rsharar
