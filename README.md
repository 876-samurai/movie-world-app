# Movie World

Movie World is a React-based web application that allows you to search for movies using the OMDB API and displays the search results in an organized and visually appealing manner. You can search for movies by their titles and get information about them, including the release year, poster, type, and title. This README will provide you with information on how to get started with the project and how to contribute. This project is great to use to undestand the basic concepts of React.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Prerequisites

Before you get started with Movie World, make sure you have the following prerequisites:

- Node.js: Ensure that you have Node.js installed on your system. You can download it from [nodejs.org](https://nodejs.org/).

## Installation

Follow these steps to set up Movie World on your local machine:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/movie-world.git
   ```

2. Navigate to the project directory:

   ```bash
   cd movie-world
   ```

3. Install the project dependencies using npm:

   ```bash
   npm install
   ```

4. Get an API key from [OMDB API](http://www.omdbapi.com/apikey.aspx) and replace `"YOUR_API_KEY"` with your actual API key in the `API_URL` constant in the `App.js` file.

## Usage

To run Movie World locally, execute the following command:

```bash
npm start
```

This will start the development server, and you can access the Movie World app in your web browser at `http://localhost:3000`.

Once the app is running, you can:

- Enter a movie title in the search bar and click the search icon to retrieve information about movies.
- View search results, including the movie's release year, poster, type, and title.
- If no movies are found, a message will inform you.

Enjoy using Movie World to explore the world of movies!
