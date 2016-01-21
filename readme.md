## Learning Experiences

###[AJAX, API, JSON, and XMLHttpRequests](https://coursework.galvanize.com/redirects/learning_experiences/34)

- LE - 6

###[AJAX Extended](https://coursework.galvanize.com/redirects/learning_experiences/105)
- LE - 2

###[Intro to the DOM](https://coursework.galvanize.com/redirects/learning_experiences/83)
- LE - 10

## Overview

Over the last week we have covered all the topics within this project. So now it's time to put a bunch of them together!! In this exercise we'll be using jQuery, AJAX calls and web api's to build a search tool that allows a user to input something and get back relevant information. It's pretty much google. Yeah. Let's make google. Only better...

### Steps

1. Have a look at the APIs listed below, and choose one you think looks cool/interesting/fun.
1. Create a basic project structure with index.html, styles.css and main.js.
1. Make sure you're including jQuery in your script tags.
1. Add a ```console.log('sanity check')``` in your main.js file within a document.ready function to ensure that jQuery is set up correctly and will only run once your page has fully loaded.
1. Go to the URL for your chosen API, and have a read through the documentation.
1. Think about what you want the user to be able to search for and which results you would like displayed on your page.
1. Find the URL for that information in the API documentation. This can sometimes be tricky!! Check URLS using curl or postman, and try out different parameters.
1. Go back to your html page and add an input box to allow the user to input stuff, and a submit button.
1. Write a function using jQuery so when a user clicks the button, their browser will log something to the console. This step is just to ensure that your function is written correctly and that when a user clicks the button, something will actually happen.
1. Within your onclick function for the submit button, write an ajax request that will hit the endpoint URL you have chosen for your API, and console.log the information you recieve back.
1. At this point it is always useful to go into your console within your browser and look through the data that is actually being returned.
1. Work out how to pull out the bits you want from all the data you are being returned. With API's, you will often find data is nested, and it may take a bit of thought/hacking to work out exactly how to access it.
1. Next, you will have to use your super amazing DOM manipulation skills to have the information you're getting back from your ajax request show up on your webpage. You can display images, text, links, etc... whatever it is you have chosen to display to your user.
1. We now currently have a button that hits one endpoint and will only ever return the information from the URL we have hardcoded. How would we make this dynamic?
1. In order to make it dynamic, we want the user to enter some text into the input box, take that text, and insert it into the string URL we have in our javascript file.
1. To do this you will have to  work out what section of that string URL needs to be changed to return different information, specifically, what the user has requested.
1. This will mean that when the user clicks submit, the endpoint URL will contain the parameters the user has specified, and return the data the user has requested.
1. Make your page look nice!!! Style it so it looks awesome.


#### Stretch Goals

1. Add another input box to edit the users search further e.g. return only x results, then use this value to perform logic on the result in your jQuery function
1. Build a function that will perform an ajax request as soon as the page is loaded, so that there is information already on the page before the user performs a search
1. Use multiple APIS. How could you use the information returned from one api, to do something with another one? e.g. get movie information from OMDB, then find the soundtrack to it using spotify

### [OMDB](http://www.omdbapi.com/)

- Build a search page in html that will allow the user to enter parameters and return information that matches what they have searched for e.g. movie plots, ratings, release dates

### [Spotify](https://developer.spotify.com/web-api/)

- Build a search page that allows user to search for artists of their choice and return information about that artist e.g. albums, songs and will then display those albums and the images related to them

### [Github](https://developer.github.com/v3/)

- Build a page that will allows users to find information on other github user profiles and then display that information as it comes back. Pick what information you want to display and how you would like the end user to see it

### [Pokemon API](http://pokeapi.co/)

- Build a page that allows users to compare pokemon stats and moves, as well as descriptions of the pokemon

### [Itunes search API](https://www.apple.com/itunes/affiliates/resources/documentation/itunes-store-web-service-search-api.html#searchexamples)

- Build a search page that will let users search for artists and display the artwork from their albums in a user-friendly way on the website
