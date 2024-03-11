# aamusted-navigation-app-v1
A web application for the navigation of the Akenten Appiah-Menka University of Skills Training and Entrepreneurial Development (AAMUSTED) Campus that enables shortest-route calculation between buildings and other locations. Builds off the leaflet javaScript library and the Mapquest API in a campus-oriented way. Built to be highly scalable, such that other campuses can customize the app for their own campus.

The primary goal of this project is to enable campus-oriented and intuitive navigation on the Akenten Appiah-Menka University of Skills Training and Entrepreneurial Development (AAMUSTED) campus. On the left sidebar, the first dropdown is for navigation (i.e., calculating the shortest path between two locations). To navigate between two locations, choose your "Starting Point" in the top selection, your "Destination" in the bottom selection, and click the “Navigate” button. One can also select locations by hovering over them and clicking on them. If the selections are invalid, an alert will appear asking you to try again, and the navigation request will fail.

The next three dropdowns enable you to easily search for AAMUSTED locations and, when clicked, locate them on the full-screen map. In the fifth dropdown, there is an option to send feedback to the developers through SMTP servers. The final dropdown describes the developers briefly. The left sidebar can be entirely collapsed (and reopened) by clicking the website logo immediately to the right of the sidebar to get a better view of the map.

On the horizontal bar, the starting point and destination selected in the left sidebar are listed first. Following is the total distance along the recommended path from these locations in miles and the estimated time of arrival in minutes. Next is a weather icon that shows the current weather in Kumasi, using the OpenWeatherMaps API. If you click the icon, a popup will drop down from the icon with more details about the icon itself, the current temperature in two units, the windspeed, and another icon recommending whether or not to bring an umbrella. If the icon is clicked again, the popup will close.

To the right of the weather icon is an option to display your current location using a browser API. If the user is outside the Akenten Appiah-Menka University of Skills Training and Entrepreneurial Development (AAMUSTED) campus, an alert will appear stating that the website is best-suited for navigation within the campus and has limited functionality beyond it. The next icon, the GitHub logo, takes you to our public GitHub repository when clicked. The coffee-cup icon (which is currently not a released feature) gives the user the option to “buy us a coffee” or donate money to our website’s further development. Finally, the right-most switch on the horizontal bar changes the theme of the entire webpage to an alternate dark-mode theme.

     TO DO LIST
1[] add a push notificatio the map
    *this should notify students when they have lectures and where.

2[]add a share location feature to the map
   *this will allow student to share their locatio to colleages for directions

3[] add a examination venu markers to the map

4[done]add a weather api using openweather API

