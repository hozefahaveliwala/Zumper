## Take Home Assignment from Zumper

This Android App includes the following functionalities:

 - App opens to a map which displays restaurants in San Francisco area.
 - It provides additional feature to search restaurants in any area via an Auto Complete Search View powered by Google Places API.
 - The map is auto zoomed to provide the best view of almost all the markers.
 - Clicking on a marker displays its Name and Address on the marker.
 - Clicking on the information opens a new screen with all the details.
 - The second screen houses the details of the restaurant in an elegant and crisp UI.
 - It provides swipe down feature to refresh the details. Also detects network connectivity and performs tasks accordingly.
 - Contact information of the restaurant is displayed and can be used directly to open call dial screen/browser window.
 
 - Have used libraries like Retrofit, GSON, Picasso to handle API calls, JSON parsing and image rendering.
 - ---
 ## Extra Addons
 - BroadCast Receiver used to auto detect internet availability and refreshes the information.
 - Floating button to open filtering options
 - Filtering options on radius, maxprice and open only restaurants.
 - Filtering options embedded in a Bottom Navigation Sheet.
 - Tried embedding the API KEY into BuildConfig but did not succeed.