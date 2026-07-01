# MindForge

A professional quiz and puzzle platform designed to sharpen minds through engaging challenges.

## Features

- **Quiz Mode**: Timed quizzes with progress tracking
- **Puzzle Challenges**: Logic puzzles and riddles
- **Leaderboard**: Track top scores
- **Question Bank**: 1000+ questions across multiple categories
- **Responsive Design**: Works seamlessly on desktop and mobile
- **Score Tracking**: Store and review results

## Getting Started

### Prerequisites
- Node.js (v16+)
- npm or yarn

### Installation

```bash
npm install
npm run dev
```

The app will open at `http://localhost:5173`

### Build for Production

```bash
npm run build
npm run preview
```

## Project Structure

```
src/
├── components/          # Reusable components
├── pages/               # Page components (Landing, Quiz, Puzzle, Results)
├── utils/               # Utility functions (parsing, shuffling, scoring)
├── styles/              # Global styles
├── data/                # Question data (questions.txt and parser)
├── App.jsx              # Main app component with routing
└── main.jsx             # Entry point
```

## Question Format

Questions are stored in `src/data/questions.txt` with the following format:

```
Q: Question text here?
A: Option A
B: Option B
C: Option C
D: Option D
Correct: A

Q: Next question?
A: Option A
B: Option B
C: Option C
D: Option D
Correct: B
```

Separate each question with a blank line.

## Features Implemented

✅ Landing page with hero section and feature cards
✅ Quiz page with timer and progress tracking
✅ Puzzle page with interactive challenges
✅ Results page with score summary
✅ 1000+ questions across 10+ categories
✅ Fisher-Yates shuffling algorithm
✅ Responsive design for mobile and desktop
✅ Modern corporate styling
✅ localStorage for score tracking
✅ React Router navigation

## Technologies

- **Frontend**: React 18
- **Routing**: React Router v6
- **Styling**: Styled Components
- **Build Tool**: Vite
- **Node**: v16+

## License

MIT
