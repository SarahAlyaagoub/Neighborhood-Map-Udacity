# Neighborhood_Map (udacity - project 5)
Demo: https://sarahalyaagoub.github.io/Neighborhood-Map-Udacity/

# What Does it Do?
It displays a map and side menu where you can manage and filter location markers on the map.
If you click any marker, it will query Wikipedia API to display content in the info window. 

     

# App Architecture
- It uses KnockoutJS (KO) framework that follows MVVM pattern. (http://knockoutjs.com/)
- KO avoids updating the DOM manually with jQuery or JS, and uses observables rather than forcing refreshes manually. 
- There are 5 locations in the model. 

# App Functionality
- Includes a text input field that filters the map markers and list items to locations matching the text input or selection.
- Clicking a location on the list displays info window about the location, and animates its associated map marker.
  

# APIs used in the project
- Google Maps API allow for the embedding of Google Maps onto web pages with markers using javascript.
- Google Fonts API to add fonts to your web pages (https://goo.gl/GZuU8y)
- Media Wiki API (Wikipedia) provided additional data about a location in the marker's infoWindow (https://www.mediawiki.org/wiki/API:Main_page).
    
    
    
# To Open This File:
- Clone/Download the repo
- Open index.html - or run it on a local server.


# How to Run it on a local server?
- make sure ngrok and python are both installed in your laptop (python 2 in this case is downloaded).
- move ngrok file inside your project directory
- open terminal window, and type cd the/path/of/your/directory
- Once you are inside the directory, type python -m SimpleHTTPServer 8080 
- open another terminal window, cd the/path/of/your/directory 
- once you are inside the directory, type ./ngrok http 8080 
- copy the link next to 'forwarding', paste it on your browser and view the website locally.







    
    
