# Spotifynder Onboarding1 Feature

## Overview
The onboarding1 feature of **Spotifynder** guides users through a multi-step setup process. The steps include:

1. Signing in with Spotify (simulated button)
2. Selecting a college
3. Choosing top artists and tracks

Data is stored in `IndexedDB` to ensure session persistence, allowing users to return to their selections if they reload or revisit the app. The design focuses on responsiveness and a user-friendly interface.

## Features

### 1. Sign-in Page
   - **Description**: A simple start page with a "Sign in with Spotify" button to initiate the onboarding process.
   - **Purpose**: Begins the user journey with a familiar entry point.
   - **Points**: 1 point (Small feature)

### 2. College Selection Page
   - **Description**: A form where users can input their college name. The data is saved in `IndexedDB` upon submission.
   - **Purpose**: Collects college information for filtering users by location.
   - **IndexedDB**: Stores the college name.
   - **Points**: 2 points (Medium feature due to form handling and database integration)

### 3. Top Artists and Tracks Selection
   - **Description**: Allows users to select up to three artists and three tracks from a predefined list. Selections are visually highlighted, and data is stored in `IndexedDB`.
   - **Purpose**: Gathers information on music preferences to improve matchmaking.
   - **IndexedDB**: Stores selected artists and tracks.
   - **Scrolling Feature**: Allows users to scroll through a list if items exceed the viewport.
   - **Points**: 3 points (Medium feature due to selection highlighting, `IndexedDB` integration, and scrolling)

### 4. Finish Button and Completion
   - **Description**: Finalizes the onboarding process, confirming that all selected data is saved. Users are notified of completion.
   - **Purpose**: Provides a clear end to onboarding and prepares the user for the main application.
   - **IndexedDB**: Ensures all data is saved before completion.
   - **Points**: 2 points (Medium feature)

### 5. Responsive Design and Styling
   - **Description**: Responsive CSS ensures usability across devices, with media queries for optimal layout on various screen sizes.
   - **Purpose**: Enhances user experience by making the interface adaptable.
   - **Points**: 2 points (Medium feature)

## Total Points: 10




