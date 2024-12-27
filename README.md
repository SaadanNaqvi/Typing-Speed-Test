Typing Speed Test Application

Overview

This Typing Speed Test application is a web-based tool designed to measure a user's typing speed (words per minute) and accuracy. Users can test their typing skills against a randomly generated text, view their results, and compare their performance on a leaderboard.

Features

Dynamic Typing Test:

Displays a randomly fetched paragraph for users to type.

Highlights correct and incorrect letters in green and red, respectively.

Live Metrics:

Tracks and displays real-time typing speed (words per minute) and accuracy percentage.

Stopwatch:

Starts automatically when the user begins typing.

Records the elapsed time for the test.

Completion Detection:

Automatically ends the test when the user types all characters in the given text.

Leaderboard:

Stores the top 5 scores in the browser’s local storage.

Displays username, typing speed, and accuracy.

Technologies Used

HTML: For structuring the user interface.

CSS: For styling the application (via style.css).

JavaScript: For dynamic behavior, stopwatch functionality, real-time performance tracking, and local storage management.

File Structure

index.html: Main file containing the structure of the application.

style.css: External stylesheet for styling the user interface.

script.js (optional): JavaScript code for enhanced modularity.

Instructions to Use

Open the Application:

Load index.html in any modern web browser.

Enter Username:

A prompt will ask for the user's name, which is stored for leaderboard purposes.

Start Typing:

Click the Start Typing button to fetch a random paragraph and begin the test.

Begin typing in the provided textarea.

Submit:

Click the Submit button or press Enter to finalize results manually.

View Leaderboard:

The leaderboard updates automatically with the top 5 scores.

Key Functions

1. Fetching Text

Fetches a random paragraph from the API (http://metaphorpsum.com/paragraphs/1/2).

Initializes the text to type and resets metrics.

2. Stopwatch

Tracks elapsed time in hours, minutes, and seconds.

Updates every second during the test.

3. Typing Metrics

Accuracy: Calculated as (Correct Characters / Total Typed Characters) * 100.

Speed: Measured in words per minute based on the elapsed time.

4. Leaderboard

Stores top 5 scores locally using localStorage.

Displays the leaderboard dynamically.

Additional Features

Auto-Completion: Automatically stops the test and displays results when the user finishes typing the text.

Error Handling: Alerts the user if the test is submitted without typing.

Text Highlighting: Differentiates correct and incorrect characters visually.

Future Improvements

Add support for customizable difficulty levels.

Integrate a backend for storing user scores persistently.

Enhance UI with animations and themes.

Provide detailed analytics such as most common errors and typing patterns.

Author

[Your Name]

This project is a beginner-friendly implementation to practice JavaScript, DOM manipulation, and web application development.
