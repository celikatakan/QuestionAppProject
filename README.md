# Quiz Application

This project is a quiz application developed based on the following requirements. Users can solve a 10-question quiz within specific rules and view their results.

## Project Features

### Design
- The project design is fully customized and usable with a width of 1400px.

### Home Screen
- A home screen includes a "Start Test" button and information about the quiz.

### Question Flow
- The quiz consists of a total of 10 questions.
- Users can stay on each question screen for a maximum of 30 seconds.
- The answer options are not displayed for the first 4 seconds.
- Once an answer is selected, the next question appears without waiting for 30 seconds to elapse.
- It is not possible to return to previous questions.

### Results
- At the end of the quiz, the user is shown the number of correct, incorrect, and unanswered questions.

## Technologies Used

- **React:** Used for developing the application.
- **Vite:** Used for the development and build process of the React project.
- **CSS:** Used for styling.

## Project Structure

```
src/
├── components/
│   └── Quiz.jsx      # Component managing the quiz and question screen
├── App.jsx           # Main component of the application
├── App.css           # Global styles
├── index.css         # Base CSS file
├── main.jsx          # Entry point of the React application
├── questions.js      # File containing the questions
public/
├── t-rex.jpg         # Image file related to the quiz
```


[Netlify](https://questionappproject.netlify.app/)
