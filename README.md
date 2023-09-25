
#  Blackjack {Python Game}
This is a simple text-based Blackjack game implemented in Python. Here's a breakdown of the different parts:

1. `deal_card()`: This function returns a random card from the deck. The deck is represented as a list of numbers, where 11 represents an Ace, and 10 can be 10, Jack, Queen, or King.

2. `calculate_score(cards)`: This function calculates the score of a hand in Blackjack. It checks if the hand is a blackjack (a two-card hand that sums up to 21), and if so, returns 0. It also checks if the hand contains an Ace (represented as 11) and if the total score of the hand exceeds 21. If so, it changes the Ace's value from 11 to 1.

3. `compare(user_score, computer_score)`: This function compares the user's score and the computer's score and returns a string that declares the result of the game.

4. `play_game()`: This is the main game loop. It first deals two cards each to the user and the computer. Then it enters a loop where it continually asks the user if they want another card or if they want to pass. If the user's score reaches 0 (blackjack) or exceeds 21, or if the user decides to pass, it ends this loop. Then it lets the computer draw cards until its score is 17 or higher. Finally, it compares the user's and computer's scores and declares who won.

5. The last part of the code is a loop that continually asks the user if they want to play a game of Blackjack, and if so, calls `play_game()` to start a new game.

This code uses functions from Python's built-in `random` module to draw random cards from the deck, and it uses simple control flow structures (like `if` statements and `while` loops) to implement the game logic.
[assistant]=(#message)
#  Acknowledgements
I would like to thank Dr. Angela Yu.
## Authors

- [@Sookchand](https://github.com/Sookchand)


## Screenshots

![blackjack](https://github.com/Sookchand/Blackjack/assets/34344439/d8daa21b-926f-4d41-8205-ae78d6f00611)



## Tech Stack
The game is a simple text-based Blackjack game implemented in Python. Here are the technologies and concepts used in creating this game:

1. **Python**: This is the programming language used to write the game. Python is known for its simplicity and readability, which makes it a great language for beginners.

2. **Random Module**: This built-in Python module is used to generate random numbers. In this game, it's used to randomly select a card from the deck.

3. **Functions**: The game uses several functions to encapsulate different parts of the game logic. This makes the code easier to understand and maintain.

4. **Control Flow Structures**: The game uses `if` statements and `while` loops to control the flow of the game. These are fundamental concepts in most programming languages.

5. **Lists**: The game uses lists to represent the deck of cards and the hands of the player and computer. Lists are a type of data structure that can hold multiple items.

6. **Input/Output**: The game uses Python's built-in `input()` function to get input from the user, and it uses `print()` statements to display information to the user.

7. **Import Statement**: The `import` statement is used to include external modules (like `random`) into the program.

8. **Comments**: Comments (lines starting with `#` or enclosed in triple quotes `'''`) are used to explain what different parts of the code do.

So, while this game might seem simple, it actually incorporates several important programming concepts and makes use of various features of the Python language.
## Documentation
Here are the documentations for the technologies used in creating the game:

1. **Python**: Python is the programming language used to write the game. You can find more about Python in its official documentation¹².
   

3. **Random Module**: This built-in Python module is used to generate random numbers. You can learn more about it in its official documentation⁵.


4. **Functions**: Functions are used to encapsulate different parts of the game logic. You can learn more about functions in Python from its official documentation⁹.


5. **Control Flow Structures**: The game uses `if` statements and `while` loops to control the flow of the game. These are fundamental concepts in most programming languages. You can learn more about control flow structures in Python from its official documentation¹³¹⁴.


6. **Lists**: The game uses lists to represent the deck of cards and the hands of the player and computer. Lists are a type of data structure that can hold multiple items. You can learn more about lists in Python from its official documentation¹⁶.


7. **Input/Output**: The game uses Python's built-in `input()` function to get input from the user, and it uses `print()` statements to display information to the user. You can learn more about input and output in Python from its official documentation[^20^]²¹.


8. **Import Statement**: The `import` statement is used to include external modules (like `random`) into the program. You can learn more about import statement in Python from its official documentation²²²³²⁴²⁵.


9. **Comments**: Comments (lines starting with `#` or enclosed in triple quotes `'''`) are used to explain what different parts of the code do. You can learn more about comments in Python from these resources[^10^]²⁶²⁷²⁸²⁹[^30^].

Source: Conversation with Bing, 9/25/2023.


(1) Our Documentation | Python.org. https://www.python.org/doc/.

(2) Python 3.11.5 documentation. https://docs.python.org/.

(3) random — Generate pseudo-random numbers — Python 3.11.5 documentation. https://docs.python.org/3/library/random.html.

(4) Built-in Functions — Python 3.11.5 documentation. https://docs.python.org/3/library/functions.html.

(5) 4. More Control Flow Tools — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/controlflow.html.

(6) Python Control Flow Statements and Loops – PYnative. https://pynative.com/python-control-flow-statements/.

(7) 5. Data Structures — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/datastructures.html.

(8) 7. Input and Output — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/inputoutput.html.

(9) Basic Input, Output, and String Formatting in Python. https://realpython.com/python-input-output/.

(10) 5. The import system — Python 3.11.5 documentation. https://docs.python.org/3/reference/import.html.

(11) 7. Simple statements — Python 3.11.5 documentation. https://docs.python.org/3/reference/simple_stmts.html.

(12) importlib — The implementation of import — Python 3.11.5 documentation. https://docs.python.org/3/library/importlib.html.

(13) Python import: Advanced Techniques and Tips – Real Python. https://realpython.com/python-import/.

(14) Documenting Python Code: A Complete Guide – Real Python. https://realpython.com/documenting-python-code/.

(15) Writing Comments in Python (Guide) – Real Python. https://realpython.com/python-comments-guide/.

(16) Create documentation comments | PyCharm Documentation - JetBrains. https://bing.com/search?q=Python+Comments+documentation.

(17) Create documentation comments | PyCharm Documentation - JetBrains. https://www.jetbrains.com/help/pycharm/creating-documentation-comments.html.

(18) Python Comments - Python Tutorial. https://www.pythontutorial.net/python-basics/python-comments/.

(19) Comments, Docstrings, and Type Hints in Python Code. https://machinelearningmastery.com/comments-docstrings-and-type-hints-in-python-code/.

(20) Python Developer's Guide | Python.org. https://www.python.org/dev/.

(21) The Python Language Reference — Python 3.11.5 documentation. https://docs.python.org/3/reference/index.html.

(22) Python Random Module - W3Schools. https://www.w3schools.com/python/module_random.asp.

(23) Python Random Module: Generate Random Numbers and Data - PYnative. https://pynative.com/python/random/.

(24) random – pseudo-random numbers and choices - CircuitPython. https://docs.circuitpython.org/en/latest/shared-bindings/random/index.html.

(25) Functional Programming HOWTO — Python 3.11.5 documentation. https://docs.python.org/3/howto/functional.html.

(26) How to Document Functions in Python - codingem.com. https://www.codingem.com/python-how-to-document-functions/.

(27) Python Control Flow - Python Cheatsheet. https://www.pythoncheatsheet.org/cheatsheet/control-flow.

(28) Python List (With Examples) - Programiz. https://www.programiz.com/python-programming/list.

(29) Python Lists | Python Education | Google for Developers. https://developers.google.com/edu/python/lists.

(30) Lists, Tuples and Dictionaries - Python 101 1.0 documentation. https://python101.pythonlibrary.org/chapter3_lists_dicts.html.

(31) undefined. https://devguide.python.org/.
## Lessons Learned
Developing a game like this can teach you several important lessons:

1. **Understanding of Python**: Developing this game can help you understand the basics of Python, including data types, control flow structures, functions, and modules.

2. **Problem-Solving Skills**: Writing a program to implement a game requires you to break down the problem into smaller, manageable parts. This can improve your problem-solving skills.

3. **Debugging Skills**: If you encounter errors or unexpected behavior while developing the game, you'll need to figure out what's causing the problem and how to fix it. This can improve your debugging skills.

4. **Understanding of Game Logic**: Implementing a game requires you to understand and correctly implement the game's rules and logic. This can improve your understanding of how games work and how to implement them in code.

5. **User Interaction**: The game involves getting input from the user and displaying output to the user. This can improve your understanding of how to interact with users in a program.

6. **Code Organization**: The code for the game is organized into functions, each of which performs a specific task. This can improve your understanding of how to organize code effectively.

7. **Importance of Comments**: The code includes comments that explain what different parts of the code do. This highlights the importance of including comments in your code to make it easier for others (and yourself) to understand.

8. **Real-World Application**: Finally, developing a game like this can show you how the concepts and skills you're learning can be applied to create a real-world application.
[assistant]=(#message)\<assistant>\

# Hi, I'm Sookchand! 👋

Strive to improve with each passing moment, surpassing the person I was in the previous minute, the previous hour, and even the person you were yesterday.
## 🚀 About Me
I have experience as a data scientist and machine learning engineer. I have worked on projects involving the development of predictive models, the optimization of machine learning algorithms, and the deployment of machine learning models. I have also worked on projects involving the analysis of large datasets, the development of data-driven insights, and the creation of data visualizations.
## 🛠 Skills
I possess a wide range of skills including:

- **Data Analysis**: Proficient in Data Exploration and Visualization, Model Evaluation and Analysis, and Regression Analysis.
- **Machine Learning**: Experienced in Neural Network and Deep Learning, Supervised Learning (including Classification, Regression, and Time Series), Decision Trees and Random Forests, Ensemble Learning, and Hyperparameter Tuning.
- **Libraries and Frameworks**: Skilled in using TensorFlow 2.0, NumPy, Scikit Learn, Keras, Pandas, React.js, Node.js, Express.js with Node.js.
- **Big Data Technologies**: Familiar with Hadoop, Apache Spark, Kafka, and Apache Flink.
- **Image Processing**: Capable of performing Image Recognition and Classification, and Transfer Learning.
- **Programming Languages**: Proficient in Python and R. Also have experience with HTML, CSS, JavaScript ES6, DOM, JQuery.
- **Database Management**: Knowledgeable in SQL and MongoDB along with Mongoose.
- **Web Development**: Experienced in HTML, CSS, Bootstrap 4, JavaScript ES6, DOM, JQuery.
- **Version Control Systems**: Comfortable with Git, GitHub.
- **Data Visualization Tools**: Proficient in Tableau and Power BI.
- **Authentication and Security**: Familiar with various authentication and security protocols.
- **Other Skills**: Comfortable working with GPU on Google Collab. Familiar with Unix Command-Line.

This diverse skill set allows me to tackle a variety of data science and web development projects.
