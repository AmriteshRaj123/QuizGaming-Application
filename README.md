# MCQ Game App

This is a captivating ReactJS MCQ game application featuring one-question-per-screen navigation, a user-friendly design, and a final score display upon completing the questions.

## Table of Contents

- [Features] (#features)
- [Installation] (#installation)
- [Usage] (#usage)
- [Project Structure] (#project-structure)
- [Components] (#components)
- [Styling] (#styling)
- [Deployment] (#deployment)



## Features

- One-question-per-screen navigation.
- User-friendly design.
- Displays the final score upon completion of all questions.

## Installation

### Prerequisites

- Node.js and npm installed on your machine.

### Steps

1. **Clone the repository:**
   - Download the project code from GitHub .
     Github link :- https://github.com/AmriteshRaj123/Quiz-Game-App.git

2. **Install dependencies:**
   - Run `npm install` to install all necessary packages.

3. **Start the development server:**
   - Run `npm start` to start the application on `http://localhost:3000`.

## Usage

- Navigate through the questions by selecting an answer.
- Each correct answer increases your score.
- At the end of the quiz, your final score will be displayed.



## Project Structure

- **public/**: Contains the HTML file and static assets.
- **src/**: Contains the React components, CSS files, and other assets.
  - **components/**: Contains individual React components.
  - **App.js**: Main application component.
  - **App.css**: Main stylesheet for the application.

## Components

### Question Component

- Responsible for displaying the question and the multiple-choice options.
- Takes props for the question text, options, and a callback function to handle the user's answer.

### Quiz Component

- Manages the state of the quiz, including the current question index and the user's score.
- Handles the logic for progressing through questions and calculating the final score.
- Conditionally renders either the current question or the final score based on the state.

### Score Component

- Displays the user's final score after all questions have been answered.

### App Component

- The main component that renders the `Quiz` component.
- Includes basic structure and styling for the application.

## Styling

- **App.css**: Contains styles to ensure the application is visually appealing and user-friendly.
  - Centers content.
  - Styles buttons and containers for better user interaction.

## Deployment

### Deploy on Vercel

1. **Install Vercel CLI:**
   - Use `npm install -g vercel` to install Vercel globally.

2. **Deploy the project:**
   - Run `vercel` and follow the prompts to deploy the application.

3. **Live URL:**
   - Your deployed app will be accessible via a URL provided by Vercel.
   - Vercel link :- https://quiz-game-app-six.vercel.app/  

# QuizGaming-Application
