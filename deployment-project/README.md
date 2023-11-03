## Crush Club - Wine Lovers 🍷
> A Web Application for Wine Lovers that allows users to add reviews to help bring together a community of wine enthusiasts and help them share their experience and recommendations.
#### Users
  - Wine enthusiasts and anyone interested in learning and joining a community of wine lovers.
  - Individuals looking for wine recommendations and reviews.
  - Wineries and wine producers interested in getting feedback from the community.
#### Key Functions for Users
  - Connects wine lovers to a vibrant community.
  - Provides a platform to share their wine experiences.
  - Facilitates the discovery of new wines through reviews and recommendations.

#### Key Features:
  - Post Reviews: The backend allows users to submit reviews for specific wines. When users post a review, the backend stores the review data and associates it with the respective wine in the database.
  - Get Wines: Users can retrieve information about available wines from the backend. The backend handles requests to provide users with a curated selection of wines for exploration, which is a central feature of the application.

## Technologies
- Language: Java (Version: 17).
- Framework: Spring Boot (Version: 3.0.5).
- Build automation tool: Maven.
- Database: MongoDB.
- Lombok library: Used to reduce boilerplate code by generating common methods (e.g., getters, setters, constructors) through annotations.
### Deployment Tool
- Railway CLI.
- CI/CD: GitHub Actions workflow.

## Competencies
### Competency Checklist -  Software Engineering
#### Job Function: 3.6

- _Can implement a RESTful API?_
  - _Actions:_
     - I have defined endpoints for retrieving information about wines and saving user reviews, which are key components of a RESTful API.
     - The endpoints follow the common RESTful conventions:
          - GET /wines: This endpoint is used to retrieve a list of all wines stored in the MongoDB database. It follows the RESTful convention for retrieving resources.
          - GET /wines/{id}: This endpoint is used to retrieve information about a specific wine stored in the database, identified by its imdbId. It follows the RESTful convention for retrieving a specific resource by its identifier.
          - POST /reviews: This endpoint is used to save new reviews to the database for a specific wine, and it follows the RESTful convention for creating or adding a resource
  - _Results:_
      - The API I created allows the Crush Club - Wine Lovers website to easily find and display information about different wines and lets users share their reviews.
