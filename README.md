Online Quiz is an Online Test Application that allows users to take quizzes, review their answers, and see their results. The application has three main modules: Quiz, Review, and Result.
Main Features:
1.	Quiz Module:
o	Users can start the quiz by clicking the start button on index.html.
o	The quiz comprises a set of sports-related questions in JSON format.
o	When a user selects an answer, they immediately receive feedback indicating if their answer is correct or incorrect, with correct answers highlighted in green and incorrect ones in red.
o	Questions are stored and fetched using the Fetch API.
2.	Review and Result Module:
o	After completing the quiz, users can review their answers.
o	The final score is displayed at the end of the quiz.
o	Scores are stored and retrieved using localStorage.setItem() and localStorage.getItem() functions.
Technologies Used:
•	HTML and CSS: For structuring and styling the application.
•	JavaScript: For handling quiz logic, user interactions, and Fetch API.
•	JSON: For storing and sharing quiz questions.
Steps to Run the Application:
1.	Start the Quiz:
o	Open index.html in a live server environment.
o	Click the start button to begin the quiz.
2.	Answer Questions:
o	Respond to each question, receiving immediate feedback on correctness.
3.	Review and See Results:
o	After completing the quiz, review your answers and see the final score.
4.	Local Server Setup:
o	Serve the index.html file locally using a server, such as the http-server npm package or Live Server extension in VS Code, for the Fetch API to function correctly.

By following these steps, you can set up and run the quiz application effectively.

