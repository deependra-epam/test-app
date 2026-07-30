# Quiz CLI

An interactive command-line quiz game for learning JavaScript concepts. This project uses Node.js and ES modules to provide a simple, engaging quiz experience in the terminal.

## Features

- Interactive category selection
- Adjustable question count
- Randomized question order
- Score tracking and progress display
- Final results summary with performance feedback
- Review of incorrect answers

## Requirements

- Node.js 18 or later

## Getting Started

### Install dependencies

```bash
npm install
```

### Run the quiz

```bash
npm start
```

## Usage

1. Start the application.
2. Choose a quiz category.
3. Select how many questions you want to answer.
4. Pick the correct answer for each question.
5. Review your score and try again if you like.

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

- `npm start` - Run the quiz application
- `npm test` - Run the test suite

## License

MIT
