
# IMDb Clone

An IMDb clone project created using React and data fetched from The Movie Database (TMDb) API.

## Overview

IMDb Clone is an online database of information related to films, television series, etc. You can find ratings and reviews for the newest movies and TV shows. The project aims to replicate the user interface and features of the popular IMDb website.

# Hosted Link 
* To view the IMDb Clone, click [here](https://boisterous-tiramisu-b540b3.netlify.app/imdb).

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Handling Routes with React Router Dom](#handling-routes-with-react-router-dom)


## Features

- View popular movies, top-rated movies, upcoming movies, etc.
- Search for movies by title.
- View movie details including cast, crew, ratings, and reviews.

## Technologies Used

- React
- JavaScript (ES6+)
- CSS (styled-components)
- The Movie Database (TMDb) API
- [Material-UI](https://mui.com) - A React UI framework

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:
   - git clone https://github.com/your-username/imdb-clone.git
2. Install dependencies:
   - cd imdb-clone
   - npm install
3. Start the development server:
   - npm start

## Usage
Users can interact with the IMDb Clone by navigating through the user-friendly interface. Key features include:

* View popular movies, top-rated movies, upcoming movies, etc.
* Search for movies by title.
* View detailed information about each movie, including cast, crew, ratings, and reviews.

## Handling Routes with React Router Dom
When using React Router Dom, it handles all the routes. However, if you directly go to an endpoint, Netlify must know where to redirect you. To address this, the IMDb Clone app uses **_/imdb_** as the endpoint to ensure proper redirection.
