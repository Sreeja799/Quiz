# Quiz

This is a simple quiz program written in Python. It provides a collection of True/False questions to the user, tracks their score, and generates the next question. The quiz questions are stored in the `data.py` file, and the program logic is implemented in the `quiz_brain.py` file. The question model is defined in `question_model.py`, and the `main.py` file executes the entire code.

## Installation

To run this program, you need to have Python installed on your system.

1. Clone the repository:

```
git clone https://github.com/your-username/your-repo.git
```

2. Change to the project directory:

```
cd your-repo
```

## Usage

1. Open a terminal or command prompt.

2. Navigate to the project directory.

3. Run the following command:

```
python main.py
```

4. The quiz will start, and you will be presented with True/False questions.

5. Enter your answer as either 'True' or 'False' (case-insensitive) and press Enter.

6. The program will display whether your answer is correct or not, along with the updated score.

7. The next question will be generated, and the process repeats until there are no more questions.

8. At the end of the quiz, your final score will be displayed.

## Files

The repository consists of the following files:

- `data.py`: Contains a list of True/False questions along with their category, type, difficulty, question, correct answer, and incorrect answers.
- `question_model.py`: Defines the `Question` class, which represents a single quiz question.
- `quiz_brain.py`: Implements the `QuizBrain` class, which handles the logic of the quiz, including score tracking, checking answers, and generating the next question.
- `main.py`: Executes the entire quiz program.


Enjoy the quiz!
