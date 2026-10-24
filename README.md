# quiz-and-flash-card
# Quiz & Flashcards

A browser app with two study modes, built with plain HTML, CSS, and JavaScript (no frameworks, no build step).

## Features
- **Quiz mode:** 15-second timer per question, scoring with a speed bonus, answer feedback, and a review of your mistakes
- **Flashcard mode:** flip cards, mark "I know it" or "Review again" until the deck is learned
- **Categories:** C, C++, Chess, Sudoku (or all mixed)
- Best score per category saved in the browser (localStorage)
- Shuffled questions and answer order on every round
- Responsive layout with automatic dark mode

## Run
Open `index.html` in your browser. That's it.

## Add your own questions
Edit `questions.js` and add an object to the list:
```js
{ category: "Python", question: "Which keyword defines a function?",
  options: ["func", "def", "function", "lambda"], answer: 1 }
```
`answer` is the index of the correct option, starting at 0. New categories appear in the menu automatically.

## Deploy for free (GitHub Pages)
Push the folder to GitHub, then go to Settings → Pages → select your branch → Save.

## Ideas to extend
- Difficulty levels
- Keyboard shortcuts (1-4 to answer)
- Load questions from a JSON file or API
- Leaderboard with a backend
- Sound effects
