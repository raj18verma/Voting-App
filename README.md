![jsr2](https://github.com/raj18verma/Voting-App/blob/master/Voting%20App%20flow%20diagram.drawio.png)

# Voting Application

This is a backend application for a voting system where users can vote for candidates. It provides functionalities for user authentication, candidate management, and voting.

## Features

- User sign up and login with Aadhar Card Number and password
- User can view the list of candidates
- User can vote for a candidate (only once)
- Admin can manage candidates (add, update, delete)
- Admin cannot vote

## Technologies Used

- Node.js
- Express.js
- MongoDB
- JSON Web Tokens (JWT) for authentication

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/raj18verma/Voting-App.git


# API Endpoints

## Authentication

### Sign Up
- `POST /signup`: Sign up a user

### Login
- `POST /login`: Login a user

## Candidates

### Get Candidates
- `GET /Candidate`: Get the list of candidates

### Add Candidate
- `POST /candidates`: Add a new candidate (Admin only)

### Update Candidate
- `PUT /candidates/:id`: Update a candidate by ID (Admin only)

### Delete Candidate
- `DELETE /candidates/:id`: Delete a candidate by ID (Admin only)

## Voting

### Get Vote Count
- `GET /candidate/vote/count`: Get the count of votes for each candidate

### Vote for Candidate
- `POST /candidates/vote/:id`: Vote for a candidate (User only)

## User Profile

### Get Profile
- `GET /user/profile`: Get user profile information

### Change Password
- `PUT /users/profile/password`: Change user password

### Don't forget to check the live working demo:- https://drive.google.com/file/d/1qGPc0fyPH0_HfmnKnxBbqRP3W4ZeI60l/view?usp=drivesdk
