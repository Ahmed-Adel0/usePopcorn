# usePopcorn App

This is a React application called usePopcorn.
It allows users to search for movies, view movie details, and add movies to a watched list.
The app utilizes custom hooks and components to manage state and handle user interactions.

## Technologies Used

1. React: A JavaScript library for building user interfaces.
2. JSX: A syntax extension for embedding HTML-like code within JavaScript.
3. HTML: Markup language for creating the structure of the web pages.
4. CSS: Style sheet language for designing the presentation of the app.
5. OMDB API: An API that provides movie information and ratings.

## Hooks Used

1. useState
   The useState hook is used to manage state within components.
   It allows components to have local state variables and provides functions to update these variables.

2. useEffect
   The useEffect hook is used to perform side effects in functional components.
   It allows components to handle lifecycle events such as component mounting, updating, and unmounting.

3. useRef
   The useRef hook is used to create a mutable reference that persists across component renders.
   It allows components to store values that persist between renders without triggering a re-render.

## Custom Hooks

1. useKey
   A custom hook that listens for a specific key press event.
   It takes a key code as input and invokes a callback function when that key is pressed.

2. useLocalStorageState
   A custom hook that manages state stored in local storage.
   It takes an initial value and a key as input and returns the current state value and a function to update the state.

3. useMovies
   A custom hook that handles movie-related functionality.
   It manages the movie list, selected movie, and watched movies.
   It provides functions to fetch movies, add a movie to the watched list, rate a movie, and delete a watched movie.

- By utilizing these custom hooks and regular hooks, the "usePopcorn" app provides optimized functionality and enhances the user experience by efficiently managing state, handling lifecycle events, and accessing DOM elements when necessary.

## Usage

To use the app, follow these steps:

1. Enter a movie title in the search bar and press Enter or click the search button.
2. The app will display a list of movies matching the search query.
3. Click on a movie to view its details.
4. If the movie is not in the watched list, you can rate it using the star rating component and click the "+ Add to list" button.
5. You can view the watched list by scrolling down on the details page.
6. To remove a movie from the watched list, click the "X" button next to the movie.
