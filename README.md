# Interactive Quiz App

This is a simple interactive quiz app built using HTML, CSS, and JavaScript. It allows users to test their knowledge in different category like: Technology, Sports, GK and English. The quiz is designed with a user-friendly interface and provides instant feedback on answers.

## Features

**HTML:**

*   **Structure:** The app utilizes semantic HTML elements such as `header`, `div`, `h1`, `h2`, `p`, `form`, `label`, `input`, `button` to structure the content and layout.
*   **Forms:** A form (`<form>`) is used to collect the user's name before starting the quiz.
*   **Input Fields:** Text input (`<input type="text">`) is used for name input.
*   **Buttons:** Buttons (`<button>`) are used for starting the quiz, submitting answers, and navigating between questions.

**CSS:**

*   **Styling:** The `front.css`, `En.css`, `gk.css`, `sport.css`, `style.css` and `caregory.css` files provide the styling for the quiz app, including layout, fonts, colors, and responsive design.
*   **Layout:** CSS is used to center the content both horizontally and vertically using flexbox.
*   **Background Image:** A background image is set for an engaging user interface.
*   **Hover Effects:** Hover effects are added to buttons for user interaction.
*   **Hidden Elements:** The class `hidden` is used to hide elements initially and reveal them dynamically using JavaScript.

**JS:**

*   **DOM Manipulation:** The app extensively uses JavaScript to interact with the DOM (Document Object Model).
*   **Event Handling:** Event listeners are used to respond to user interactions like clicking buttons and submitting forms.
*   **Dynamic Content:** JavaScript dynamically updates the quiz content, questions, and options based on user input and progress.
*   **Conditional Statements:** Conditional statements are used to check answers and provide feedback.
*   **Functions:** Functions are used to encapsulate logic, such as `startQuiz`, `showQuestion`, `checkAnswer`, and `endQuiz`.

## Functionality

1.  **Welcome Screen:**
    *   Users are greeted with a welcome message and instructions.
    *   A form asks the user to enter their name.

2.  **Category Selection:**
    *   After entering their name, users are redirected to a category selection page.
    *   Users can choose from various categories like Technology, Sports, GK, and English.

3.  **Quiz Start:**
    *   Once a category is selected, the quiz begins.
    *   The quiz interface displays the question, a timer, the number of questions completed and remaining, and the current score.

4.  **Question Display:**
    *   Questions are presented one at a time along with multiple-choice options.

5.  **Answer Selection:**
    *   Users can select an answer by clicking on the corresponding radio button.
    *   Once an answer is selected, it is immediately evaluated, and feedback is provided.

6.  **Feedback:**
    *   If the selected answer is correct, a "Correct" message is displayed.
    *   If the selected answer is incorrect, an "Incorrect" message is shown along with the correct answer.

7.  **Next Question:**
    *   After answering a question, users can click on the "Next" button to proceed to the next question.

8.  **Quiz End:**
    *   The quiz ends when all questions in the selected category are answered or when the timer runs out.

9.  **Final Score:**
    *   Upon quiz completion, the user's final score is displayed along with a message based on their performance.
    *   Users can restart the quiz with the "Restart" button, which takes them back to the category selection page.

## How to Run the Quiz App

1.  **Download the Files:** Download all the HTML, CSS, JS, image and audio files from the repository.
2.  **Open `front.html`:** Open the `front.html` file in a web browser to run the quiz app.

## File Structure

```
interactive-quiz-app/
  - front.html
  - front.css
  - front.js
  - index.html 
  - style.css
  - sport.html
  - sport.css
  - sport.js
  - En.html
  - En.css
  - En.js
  - category.html
  - caregory.css
  - gk.html
  - gk.css
  - gk.js
  - README.md 
```

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit pull requests. You can improve the quiz by:

*   Adding more questions and categories.
*   Enhancing the user interface.
*   Implementing new features like score saving or user profiles.

Let's make this quiz app even better!
