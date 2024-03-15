# Java Backend Developer Assessment - Game Monitoring API

Your task is to build a simple RESTful API server in Spring Boot that allows authenticated users to monitor players and team details in a game. Follow the instructions below to complete the assessment

## Overview

- Implement a signup and signin functionality using JSON Web Tokens (JWT) to ensure secure user access to the application.
- Upon signup, users should be assigned a random score.
- Implement role-based access control to restrict certain endpoints to authorized users only.
- Authenticated users can fetch a list of users, including the following details:
  - Rank
  - Name
  - Score
  - Team
- Create CRUD operations for teams.
  - Users can create a team with the following details:
    - Team name (required)
    - Maximum member number (should be greater than 10)
    - The user creating the team will become its owner.
  - Team owners can update team information and have the ability to reject team member requests.
  - Team owners can also delete the entire team.
  - Authenticated users can fetch a list of teams, including the following details:
    - Name
    - Owner Name
    - Total Score (summarize of member scores)
    - Member Number
    - Available Member Number
  - Authenticated users can fetch team information, including the following details for each team member:
    - Rank (total rank by score in the game)
    - Name
    - Score
- Implement appropriate error handling and validation throughout the backend to ensure data integrity and security.

## Acceptance Criteria

- Develop a Java Spring Boot backend to handle HTTP requests and responses.
- Use Spring Security and JWT for user authentication and authorization.
- Generate a random score for users upon signup.
- Implement role-based access control to protect certain endpoints.
- Design CRUD operations for teams, including creating, updating, and deleting teams.
- Allow users to join existing teams.
- Create API endpoints to retrieve team information along with details for each team member (rank, score, name).
- Ensure proper error handling and validation to prevent invalid data input and unauthorized access.

## Assessment Evaluation

- Code Quality
- Functionality
- Security
- Error Handling
- Query Performance
- Unit tests

## Bonus

- API documentation
- Dockerization

## Submission Guidelines

- Share the GitHub repository link containing your complete Java Spring Boot backend code.
- Include clear instructions on how to set up and run the application locally.

_Try your best to implement as much as you can from the given requirements_
