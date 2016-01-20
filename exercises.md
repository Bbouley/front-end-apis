##### Steps

1. Create a basic project structure with index.html, styles.css and main.js
1. Make sure you're including jQuery in your script tags
1. Add a ```console.log('sanity check')``` into your main.js to ensure that jQuery is set up correctly and you can start to code!!!
1. Go to the URL for your chosen API, and have a read through the documentation
1. Think about what you want the user to be able to search for and what results you would like to have displayed on your page.
1. Go back to your html page and add in an input box to allow the user to enter text, and a submit button
1. Link up the submit button using jQuery so that when you click on the button, your browser will log something to the console. This step is just to ensure that your function is written correctly and that when a user clicks the button, something will actually happen.
1. Within your on click function for your submit button, build an ajax request that will hit the endpoint you have chosen, and console.log the information you recieve back
1. At this point it is always useful to go into your console within your browser and check what is actually being returned
1. Work out how to access the data you want to display on the page. With API's, you will often find deeply nested data, and it may take a bit of thinking to work out exactly how to access that. Have a play around within your click function and see if you can return just the data you want to display on the page
1. Next, you will have to use your super amazing DOM manipulation skills to have things show up on your webpage. You can display images, text, links, whatever it is you have chosen to display to your user
1. We now currently have a button that hits one endpoint and will only ever return the information from the URL we have hardcoded. How would we make this dynamic?
1. In order to make it dynamic, we want the user to enter some text into the input box, take that text, and insert it into the string URL we have in our javascript file
1. This will mean that when the user clicks submit, the endpoint URL will contain the parameters the user has specified, and return the data the user has requested


##### Stretch Goals

1. Add another input box to edit the users search further e.g. return only x results, then use this value to perform logic on the result in your jQuery function
1. Build a function that will perform an ajax request as soon as the page is loaded, so that there is information already on the page before the user performs a search

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
