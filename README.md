# Quiz CLI

An interactive command-line quiz game for learning JavaScript and Node.js fundamentals.

## Overview

Quiz CLI is a terminal-based application that lets users choose a category, select the number of questions, and answer multiple-choice quiz questions. It demonstrates core JavaScript and Node.js concepts including ES Modules, async/await, file system operations, user input handling, classes, and array methods.

## Features

- Interactive terminal quiz experience
- Multiple categories:
  - JavaScript Basics
  - Node.js Fundamentals
  - General Programming
- Choice of question count per quiz session
- Randomized question order
- Instant feedback for correct and incorrect answers
- Final score summary with performance message
- Review of incorrect answers at the end

## Requirements

- Node.js 18 or later

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/deependra-epam/test-app.git
   cd test-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

Start the quiz application:

```bash
npm start
```

Or run it directly with Node.js:

```bash
node index.js
```

## How It Works

1. The app loads quiz questions from `data/questions.json`.
2. You select a category from the available options.
3. You choose how many questions to answer.
4. The quiz presents each question with multiple-choice answers.
5. Your score and performance summary are shown at the end.

## Project Structure

```text
.
├── data/questions.json
├── index.js
├── package.json
└── src
    ├── colors.js
    ├── input.js
    └── quiz.js
```

## Scripts

- `npm start` - Runs the quiz application
- `npm test` - Runs the test suite

## License

MIT
