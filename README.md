# quizGame

# Quiz Game

A simple command-line quiz game written in Go.

## Overview

This is a basic quiz game that reads questions and answers from a CSV file and quizzes the user with a time limit. The user must input their answers within the specified time.

## Features

- Reads questions and answers from a CSV file.
- Quizzes the user with a time limit for each question.
- Tracks the user's score and displays it at the end of the quiz.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/quiz-game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd quiz-game
   ```

3. Build the executable:

   ```bash
   go build quiz.go
   ```

4. Run the quiz game:

   ```bash
   ./quiz -csv=problems.csv -limit=30
   ```

   - `-csv`: Specify the CSV file containing the questions and answers. Default is `problems.csv`.
   - `-limit`: Set the time limit for the entire quiz in seconds. Default is 30 seconds.

5. Answer each question within the allotted time and see your final score.

## CSV File Format

The CSV file should have the format of "question,answer". For example:

```csv
What is the capital of France?,Paris
Who wrote 'Romeo and Juliet'?,William Shakespeare
...
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
