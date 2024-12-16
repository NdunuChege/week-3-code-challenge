# week-3-code-challenge
Flatdango Movie Theater
This code challenge is a web application that allows users to browse movies, view movie details, and purchase tickets.

Features
Movie List: Browse through the list of available movies.
Movie Details: View detailed information about each movie, including title, description, runtime, showtime, available tickets, and poster.
Buy Tickets: Purchase tickets for movies directly from the web application.
Trailer Modal: Watch trailers in a full-screen modal for an immersive experience.
Technologies Used
HTML: Used for structuring the web pages.
CSS: Used for styling the web pages, including layout, colors, and fonts.
JavaScript: Provides interactivity and dynamic content for the web pages.
JSON Server: Acts as a mock backend server to store and retrieve movie data.
File Structure
Here's an overview of the main files and directories in this project:
flatdango-movie-theater/
├── index.html        # The main HTML file
├── styles.css        # The main CSS file
├── script.js         # The main JavaScript file
├── db.json           # The JSON file for movie data
└── images/           # Directory for images
└── videos/           # Directory for videos
JSON Structure
The movie data is stored in a JSON file (db.json). Below is an example structure of the movie data:
"films": [
      {
        "id": "1",
        "title": "The Giant Gila Monster",
        "runtime": "108",
        "capacity": 30,
        "showtime": "04:00PM",
        "tickets_sold": 30,
        "description": "A giant lizard terrorizes a rural Texas community and a heroic teenager attempts to destroy the creature.",
        "poster": "https://www.gstatic.com/tv/thumb/v22vodart/2157/p2157_v_v8_ab.jpg"
      },
      {
        "id": "2",
        "title": "Manos: The Hands Of Fate",
        "runtime": "118",
        "capacity": 50,
        "showtime": "06:45PM",
        "tickets_sold": 2,
        "description": "A family gets lost on the road and stumbles upon a hidden, underground, devil-worshiping cult led by the fearsome Master and his servant Torgo.",
        "poster": "https://www.gstatic.com/tv/thumb/v22vodart/47781/p47781_v_v8_ac.jpg"
      }
Usage
Follow these steps to use the application:

Browse Movies: The list of available movies is displayed on the left sidebar. Scroll through the list to find movies you're interested in.

View Movie Details: Click on any movie in the list to view its details. The movie details will be displayed in the main section, including the poster, title, description, runtime, showtime, and available tickets.

Buy Tickets: To purchase tickets for a movie, click the "Buy Ticket" button. The available tickets count will decrease, and the button will be disabled if the movie is sold out.

Watch Trailers: To watch a trailer, click the "Watch Trailer" button. The trailer will be displayed in a modal that covers the screen for an immersive experience.

Code Structure
HTML
The index.html file contains the structure of the web application. Key elements include:

Header: Contains the logo, main heading, and a subheading.
Slider Container: A container for the continuously looping slider of movie posters.
Movie List: A sidebar listing all available movies.
Movie Details: A main section displaying details of the selected movie.
Trailer Modal: A modal for displaying movie trailers.
CSS
The styles.css file includes styles for:

Body: General styles for the body of the page.
Slider: Styles for the movie poster slider.
Header: Styles for the header and its elements.
Movie List: Styles for the list of available movies.
Movie Details: Styles for displaying movie details.
Buttons: Styles for the "Buy Ticket" and "Watch Trailer" buttons.
Modal: Styles for the trailer modal.
JavaScript
The script.js file includes:

Data Fetching: Fetching movie data from the JSON server.
Display Functions: Functions to display movie details, list of movies, and slider images.
Event Handlers: Event handlers for clicking on movie posters, buying tickets, and watching trailers.
Modal Functions: Functions to open and close the trailer modal.
Slider Animation: Code for the seamless looping slider animation.
Acknowledgements
JSON Server for providing a simple way to create a REST API.
Google Fonts for the fonts used in this project.

