# Tweet-Handle-geolocation
searching a tweet handle geolocation


This Python code uses the Google Maps Geocoding API to retrieve the coordinates of the user's location based on their profile information. 
It then retrieves the most recent tweets for the specified handle and filters them to only include tweets that have geolocation data associated with them.

The geocoded tweets are stored in a list, where each tweet is represented as a tuple containing the tweet's creation date, text, and coordinates.

The code then constructs a URL for a Google Map that is centered on the user's location, and adds a marker for each geocoded tweet to the map using the Google Maps Embed API.

Finally, the code opens the map in a web browser using the webbrowser module. You will need to replace the placeholders for your own Twitter API and Google Maps API credentials.







