# Flickr
 Call the Flickr API to retrieve the lastest 20 photos matching a search term.
 
Flickr is a photo-sharing website owned by Yahoo. Data is pulled with Flickr public key.A list of the 20 most recent photos posted to the site.
Include a "Search" link that includes a search field to let users search for photos. Application can run locally from a browser.A listener for the form submit button creates a query string from the user input for the http GET and parses the response into HTML which displays the photo  When the search term is submitted the input field and submit button are disabled during the Flickr request. They are re-enabled after the response.
Query string is built with serialize() user input or selected button text
processes JSON formated request with jQuery.getJSON. Ajax is used to retrieve the data that matches the search term from the API in JSON format.  Then each 
JSON object is iterated over and displayed on the page.

$.getJSON which takes 3 arguments 

1- URL to the resource

2- The data we want to send along with the URL. This data will affect what information Flickr will return it we get that data back in JSON format.

3-The third argument is a callback function.




