# Online-Quiz-Application

🌟  Code Flow:

🔹  Main class starts → Initialize QuizService.

🔹 Load questions → Shuffle order.

🔹 Ask each question → Show options → Read answer.

🔹 Check correctness → Update score + feedback.

🔹 After all questions → Print final score and feedback summary.

🌟 Purpose:

✅ Packages (com.app.main, com.app.model, com.app.service)

🔹 Organized code into Main, Model, and Service layers.

🔹 Improves readability, modularity, and maintainability.

✅ Class Question (Model)

🔹 Holds question text, options, and correct answer index.

🔹 Encapsulation: data is accessed only via getters.

✅ Class QuizResult (Model)

🔹 Stores total questions, correct answers, and feedback list.

🔹 Used to separate result management from quiz logic.

✅ Class QuizService (Service Layer)

🔹 Loads sample questions into a list.

🔹 Shuffles questions using Collections.shuffle() → randomness for fairness.

🔹 Runs the quiz: Displays questions, takes input, checks correctness, records results.

🔹 Validates input: Ensures only A, B, C, D are accepted.

✅ Class Main (Entry Point)

🔹 Starts JVM execution.

🔹 Creates QuizService, loads and shuffles questions.

🔹 Calls runQuiz() → returns QuizResult.

🔹 Displays final score and feedback to the user.

✅ Java Concepts Used

🔹 OOP: Encapsulation (model classes), Abstraction (service layer), Separation of Concerns (layered packages).

🔹 Collections: List for storing questions and feedback.

🔹 Loops & Conditionals: Iterating over questions and validating answers.

🔹 Scanner (I/O): Taking user input in console.

🔹 Immutability: Fields like text, options in Question are final → cannot be changed once created.

📌 References :-

🔹 I used ChatGPT to refine the grammar and structure of the key points explaining my code .

🔹 For Code Review and for exception came in the application I Used ChatGpt.

🔹 Additionally, I referred to GeeksforGeeks [https://www.geeksforgeeks.org] for conceptual guidance and coding references to ensure clarity and correctness in my implementation.
