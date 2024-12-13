
# Fitness Tracking App

## Project Overview

The Fitness Tracking App is a comprehensive fitness tracker designed to log workouts, track progress, and provide personalized fitness insights. The app allows users to authenticate, manage their workout data, and receive AI-driven workout recommendations. 

This app leverages AWS services to ensure scalability, security, and efficient data processing.

## Features

- **User Authentication and Management**: 
  - Users can create an account, log in, and manage their profile securely.
  
- **Log Workouts and Track Progress**: 
  - Users can log various workouts and track their fitness progress.
  - Built using React with `useState` to manage state, and includes `post`, `get`, and `put` methods for handling data in the backend.

- **Upload and Manage Media Files**: 
  - Users can upload and manage media files such as workout photos and videos.

## AWS Services to Use

- **AWS Cognito**: 
  - Used for user authentication and authorization, ensuring secure sign-ups and logins.
  
- **AWS Lambda**: 
  - Used for serverless backend logic to process and handle fitness data requests efficiently.
  
- **Amazon DynamoDB**: 
  - A NoSQL database used for storing user data, workout logs, and other application-related data.
  
  
- **AWS S3**: 
  - Used for storing and managing media files such as workout photos and videos.

## Installation

1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up AWS services:
    - Configure AWS Cognito for user authentication.
    - Set up AWS Lambda functions for data processing.
    - Create DynamoDB tables for user and workout data.
    - Set up Amazon S3 for media file storage.
    - (Optional) Configure SageMaker for personalized workout recommendations.

4. Run the app locally:
    ```bash
    npm start
    ```

## Usage

1. Sign up or log in to the app using AWS Cognito.
2. Log your workouts and upload any related media files.
3. Track your progress and receive personalized workout recommendations powered by AI.


### Steps for contributing:
- Fork the repo
- Create a feature branch
- Make your changes and commit them
- Push to your forked repo and submit a pull request


## Contact

For any questions or support, please reach out to us at [dadeleke31@gmail.com]      [daniget156@gmail.com]. 
