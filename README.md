# Installation
To run the Media Maven App locally, follow these steps:
Clone this repository: 
1.Install the required Python packages: **pip install -r requirements.txt**
2.Obtain a TMDB API key by signing up on the TMDB website.And put that api key inside links in details and index.html and in app.py **{your api key}**.
3.Run movies recommendation .ipynb code segments it will generate a **similarity.pkl**
4.Run the app: **streamlit run app.py**


# MediaMaven
The Media Maven App is a user-friendly web application built using Python, Streamlit, HTML, and JavaScript. This app leverages the power of the TMDB (The Movie Database) API to provide movie recommendations similar to a particular movie. 

**Features**
**Search**: Enter the title of a movie you enjoyed, and the app will retrieve relevant information about that movie.

**Recommendations**: Based on the selected movie, the app queries the TMDB API to find similar movies, taking into consideration various attributes such as genre, cast, and plot.

**Details**: View detailed information about each recommended movie, including its title, release date, synopsis, cast, and more.

**Watchlist:** Create a watchlist of movies you're interested in watching later. You can easily add and remove movies from your watchlist.

**Responsive Design:** The app is designed to be responsive and user-friendly on both desktop and mobile devices.

**Technologies Used**
**Python:** The backend of the app is built using Python, including the logic for querying the TMDB API and generating recommendations.

**Streamlit:**The user interface is created using Streamlit, a Python library for building interactive web applications.

**HTML and JavaScript:** HTML and JavaScript are used to enhance the user interface and provide additional interactivity.

**TMDB API:** The app utilizes the TMDB API to retrieve movie information and recommendations. The API provides data about movies, including details like cast, genres, and more.

If you have any questions, suggestions, or issues, please feel free to contact me hitendra369432@gmail.com
