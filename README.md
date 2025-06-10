# claude-hub-test

A collection of interactive Tic-Tac-Toe games built with React.

## Games Available

### 1. Basic Tic-Tac-Toe (`tictactoe-basic.html`)
A simple, clean implementation of the classic Tic-Tac-Toe game featuring:
- Turn-based gameplay (X and O)
- Winner detection
- Draw detection
- Game reset functionality
- Clean, minimalist UI

### 2. Enhanced Tic-Tac-Toe (`tictactoe.html`)
An advanced version with additional features:
- All basic game functionality
- Score tracking for both players and draws
- Persistent scores using localStorage
- Beautiful animations and transitions
- Winning line highlighting
- Modern, gradient-based UI design
- Mobile-responsive layout
- Color-coded players (X: red, O: teal)

## How to Play

Simply open either HTML file in a web browser:
```bash
# Open basic version
open tictactoe-basic.html

# Open enhanced version
open tictactoe.html

# Run test suite
open test-runner.html
```

No installation or build process required!

## Testing

A test runner is available at `test-runner.html` which loads both games side-by-side for testing and comparison.

## Test Report

See `test-report.md` for detailed test results and feature validation.

## Technologies Used

- React 18 (via CDN)
- Babel Standalone (for JSX transformation)
- HTML5
- CSS3 with animations
- JavaScript ES6+
- localStorage API (enhanced version)