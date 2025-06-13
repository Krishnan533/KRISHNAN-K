📘 Explanation of the Quiz Game Flow:

1. Start the Game

Display a welcome message.

Initialize score to 0.



2. Load Questions

A list of questions is stored using dictionaries (each with a question, options, and the correct answer).



3. Loop Through Each Question

For each question:

Call ask_question():

Show the question and options.

Prompt user for input (1 to 4).

If the input is correct, increment the score.

If the input is wrong or invalid, show an appropriate message.





4. End of Quiz

After all questions, show the final score.





---

🧭 Flowchart:

Here's a simple text-based flowchart:

+---------------------+
|  Start Quiz Game    |
+---------------------+
          |
          v
+---------------------+
|  Display Welcome    |
+---------------------+
          |
          v
+---------------------+
|  score = 0          |
+---------------------+
          |
          v
+---------------------+
|  Load Questions     |
+---------------------+
          |
          v
+-------------------------------+
| Loop through each question    |
+-------------------------------+
          |
          v
+-----------------------------+
| Display Question & Options |
+-----------------------------+
          |
          v
+----------------------------+
| Get user input (1 to 4)    |
+----------------------------+
          |
          v
+-----------------------------+
| Valid input?               |
+-----------------------------+
    | Yes         | No
    v             v
+----------------+   +---------------------------+
| Is answer correct? |  Show "Invalid input"     |
+----------------+   +---------------------------+
    | Yes    | No
    v        v
+----------+ +----------------------------+
| score++  | | Show correct answer        |
+----------+ +----------------------------+
          |
          v
+---------------------------+
|  All questions answered?  |
+---------------------------+
          |
          v
+------------------------+
| Show Final Score       |
+------------------------+
          |
          v
+----------------+
|     End        |
+----------------+


