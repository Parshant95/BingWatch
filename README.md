
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/rwLBS1RX)
# BingWatch.in 🎬🍿

Welcome to **BingWatch.in**, your go-to platform for exploring movies and TV shows! Discover popular titles, watch trailers, and create your personal list of favorites. 🎥✨

# Live Webiste Link
   https://bingwatchpv.netlify.app/


## About

**BingWatch.in** is a responsive web application designed to provide users with the latest movie updates, trailers, and a personalized experience. Users can search for their favorite movies, browse through popular titles, and watch trailers directly from YouTube.

## Features

- **Responsive Design**: Seamlessly adapts to different screen sizes.
- **Search Functionality**: Quickly find movies using the search bar.
- **Movie Slider**: Scrollable slider showcasing the latest movies.
- **Dynamic Grid**: Displays movies fetched from the TMDB API.
- **Trailer Links**: Watch trailers on YouTube with one click.
- **Modern UI**: Built with TailwindCSS for a sleek design.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **TailwindCSS**
- **The Movie Database (TMDB) API**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/BingWatch.git
   ```
2. Navigate to the project directory:
   ```bash
   cd BingWatch
   ```
3. Open `index.html` in your preferred browser.

---

## Usage

1. Open the homepage (`index.html`).
2. Use the navigation bar to explore:
   - **Home**: View the latest movies.
   - **Movies**: Browse all available movies.
   - **TV Shows**: Explore TV shows (coming soon).
   - **My List**: Save your favorite titles (future feature).
3. Search for movies using the search bar.
4. Click on any movie to watch its trailer on YouTube.

---

## Project Structure

BingWatch/
│
├── css/
│   ├── main.css          # Custom styles
│
├── images/
│   ├── popcorn.png       # Favicon
│   ├── img1.png          # Sample movie poster
│   ├── ...
│
├── index.html            # Main entry point
├── tvshows.html          # TV shows page
├── page.html             # My list page
├── login.html            # Login page
├── signup.html           # Signup page
└── README.md             # Project documentation


## API Integration

This project uses the **TMDB API** to fetch movie data:

- **Popular Movies**: Fetched using the endpoint:
  ```
  https://api.themoviedb.org/3/movie/popular?api_key=<YOUR_API_KEY>&language=en-US&page=1
  ```
- **Movie Trailers**: Fetched using the endpoint:
  ```
  https://api.themoviedb.org/3/movie/{movie_id}/videos?api_key=<YOUR_API_KEY>
  ```

Replace `<YOUR_API_KEY>` with your TMDB API key.

## Credits

- **The Movie Database (TMDB)**: For providing movie data and APIs.
- **TailwindCSS**: For styling and responsiveness.
- **Icons**: Popcorn icon used as a favicon.
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


### Author

Parshant Vardhan, 22BCS12914

Feel free to contribute, fork, or suggest improvements! 😊
