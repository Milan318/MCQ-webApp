# MCQ-webApp
# JavaScript Quiz App Documentation

 **Live Demo**: [mcq-web-app-tan.vercel.app](https://mcq-web-app-tan.vercel.app)
This is a web-based JavaScript Quiz App that displays multiple-choice questions (MCQs) to users. It includes features such as:

- 4 JavaScript-related questions
- Option selection with green highlight on selection
- Pagination to navigate between questions
- Timer to track the duration of the quiz
- Score display upon submission
- Hover effects and smooth animations

## Technologies Used

- **HTML** for structuring the content
- **CSS (TailwindCSS)** for styling and animations
- **JavaScript** for dynamic functionalities

## Features

1. **Questions and Options Display**

   - Questions are displayed one at a time with four options.
   - Clicking on an option highlights it in green to indicate selection.

2. **Navigation**

   - Users can navigate between questions using "Prev" and "Next" buttons.
   - Pagination does not reset the selected options.

3. **Timer**

   - A timer at the top right corner tracks the duration of the quiz.
   - Timer starts when the page loads and stops on submission.

4. **Submit and Score Display**

   - On clicking "Submit," the app calculates and displays the score.
   - Score is displayed as a fraction of correct answers over the total number of questions.

## User Interface (UI) Details

- **Quiz Card Animation**: Slight scale-up effect on hover.
- **Option Hover Effect**: Light gray background on hover for options.
- **Green Highlight**: Selected option is highlighted in green.

## Script Functionality

1. `loadQuestion()`

   - Injects the current question and its options into the DOM.
   - Highlights the previously selected option, if any.

2. `selectOption(index)`

   - Records the selected option for the current question.
   - Highlights the selected option in green.

3. `nextQuestion()` and `prevQuestion()`

   - Navigate to the next or previous question.
   - Retains the state of previously selected options.

4. `submitQuiz()`

   - Checks selected answers against the correct ones.
   - Displays the total score immediately.

5. Timer

   - Tracks time in seconds from page load to submission.

## Future Enhancements

- Add more questions with categories and difficulty levels.
- Include explanations for correct answers.
- Implement a restart option after submission.

## Conclusion

This JavaScript Quiz App is an interactive and educational tool designed to test and enhance JavaScript knowledge. With smooth animations and a user-friendly interface, it offers an engaging experience for users.

