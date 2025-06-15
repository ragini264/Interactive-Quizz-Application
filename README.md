# Interactive-Quizz-Application
*COMPANY* : CODTECH IT SOLUTIONS
*NAME* : RAGINI RAVINDRA MARATHE
*INTERN ID* : CT08QBG
*DOMAIN* : FRONT END DEVELOPMENT
*DURATION* : 4 WEEKS
*MENTOR* : NEELA SANTOSH

DESCRIPTION OF TASK :Objective of the Task

The main aim of this task is to create a quiz app that:
Presents questions to the user.
Allows users to select answers.
Provides immediate feedback (e.g., correct or wrong).
Calculates and displays the final score.
This kind of app is commonly used in educational websites, training platforms, and assessment tools, so learning to build one is very useful in the web development field.

What You Need to Do

You are asked to build a quiz application using JavaScript, which means JavaScript will control the logic and behavior of the quiz. Here are the steps you can follow to complete the task:

1. Design the Interface (Frontend Layout)

Use HTML to structure your web page:
Create a welcome screen or start button.
Add question and option placeholders.
Include buttons like Next, Submit, and Restart.
Reserve a section for score display at the end.


Use CSS to make it look good:

Style your buttons, fonts, colors, and layout.
Make the quiz responsive so it works well on mobile and desktop.

2. Write JavaScript for Quiz Logic

JavaScript will make your quiz interactive. Some of the key functions you should include:
Load and display questions one at a time.
Track which answer the user selects.
Compare the user’s answer with the correct one.
Display feedback like “Correct!” or “Oops! Wrong answer.”
Count the number of correct answers and calculate the score.
Show the final score at the end.


3. Add Dynamic Question Loading

Instead of hardcoding each question inside the HTML, store them in an array of JavaScript objects. This way, you can easily change questions or even load them from a file or API later.
Example:

let questions = [
  {
    question: "What is the capital of India?",
    options: ["Mumbai", "Delhi", "Kolkata", "Chennai"],
    answer: "Delhi"
  },
  // More questions...
];

4. Provide Instant Feedback

As soon as a user selects an answer and clicks “Next” or “Submit”, show them whether their answer was right or wrong. You can highlight the correct option in green and the wrong one in red.

5. Show Final Result

At the end of the quiz, display:
Total number of questions
Number of correct answers
Final percentage or score

