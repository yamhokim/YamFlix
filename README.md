# YamFlix

YamFlix is a react-based web application that allows users to search for different movies using the OMDb movie database API, providing them with different statistics about the movie, as well as a poster visual and general description of the movie's plot. Users can then select movies they've watched, give them a rating, and add them to a watched list to help keep track of their favourites.

## Features

- **Search Movies**: Users can search for movies by title using the OMDb API.
- **Movie Details**: View detailed information about each movie, including the title, release year, plot, and poster.
- **Watched List**: Add movies to a personal watched list.
- **Ratings**: Rate movies after watching them.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/movie-tracker.git
   cd movie-tracker
   ```

2. Install the dependencies from the package.json file:

   ```sh
   npm install
   ```

3. Create a .env file in the root directory and add your OMDb API key:

   ```sh
   REACT_APP_OMDB_API_KEY=your_api_key_here
   ```

4. Start the development server:

   ```sh
   npm start
   ```
