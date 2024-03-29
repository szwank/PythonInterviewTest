# Python Programmer Test

Please create git repository and send link to it as part of your solution.
Your task is to implement the following items into the existing project:

## 1. A class to fetch test data via https from OMDB API

- You should fetch 100 movies from OMDB API. It's up to you what kind of movies you will get.
  - Movies should be saved in the database.
  - This method should be ran only once if database is empty.
  - This method should be automated.
  
## 2. Implement an api class in the api folder for the data class

- The api should have a method that returns the list of movies from the database
  - There should be option to set how many records are returned in single API response (by default 10)
  - There should be pagination implemented in the backend
  - Data should be ordered by Title
- The api should have a method that returns single movie from the database
  - There should be option to get the movie by title
- The api should have a method to add movie to the database
  - Title should be provided in request
  - All movie details should be fetched from OMDB API and saved in the database
- The api should have a method to remove a movie from the database
  - There should be option to remove movie with it's id
  - This method should be protected so only authorized user can perform this action (There is test user in the database)

## 3. Unit tests for all classes

## 4. Surprise me :)
I have created docker image of this project
link: https://cloud.docker.com/u/szwank/repository/docker/szwank/node-web-app
