## Movix Web Application

Movix is a modern web application designed to provide users with information about movies and TV shows. With a clean and responsive user interface, the application integrates various components to offer a seamless user experience.

https://movix-mu-amber.vercel.app

### Features

- Header Navigation: Allows users to navigate between movies, TV shows, and search.

- Lazy Loading Images: Optimizes performance by loading images only when they enter the viewport.

- Movie Cards: Showcases movies and TV shows with posters, ratings, genres, and more.

- Switchable Tabs: Enables users to toggle between different categories or sections.

- Video Popup: Offers a dynamic video player popup for trailers and clips.

- Data Fetching: Efficiently fetches and manages API data with error and loading states.

### Components

Here's a breakdown of the main components used in the app:

- ContentWrapper: A generic wrapper to provide consistent styling.

- Footer: Displays site links, information text, and social media icons.

- Genres: Showcases genres associated with a movie or TV show.

- Header: Contains the main navigation bar and search functionality.

- LazyLoadImage: Uses the react-lazy-load-image-component for optimized image loading.

- MovieCard: Represents a movie or TV show card with essential details.

- Spinner: A loading spinner to indicate data fetching or other background processes.

- SwitchTabs: Allows users to switch between different tabs or sections.

- VideoPopup: A popup component that embeds a video player for trailers.

### Hooks

- useFetch: A custom hook to simplify the process of fetching data from APIs and managing associated states.

### Setup and Installation

Clone the repository:
```bash 
git clone https://github.com/FastEddyOne/Movix.git
```

Navigate to the project directory:
```bash
cd movix
```

Install the dependencies:

```npm install```

Run the development server:

```npm start```

Open your browser and navigate to http://localhost:3000 to see the application in action.

### .Env

You will need an api read access token from https://www.themoviedb.org/

```
VITE_APP_TMDB_TOKEN=
```

### Dependencies

- React: The main library used for building the user interface.

- React-Router-Dom: Used for managing application routing.

- React-Icons: For various icons used throughout the app.

- React-Player: For embedding the video player in the VideoPopup component.

- Dayjs: Lightweight library for date formatting.

- React-Redux: State management tool.

### Contributing

Contributions are always welcome!

### License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.