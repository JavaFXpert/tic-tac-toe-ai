# AI-Powered Tic Tac Toe

A single-file HTML tic-tac-toe game featuring an unbeatable AI opponent and dynamic AI-generated end messages.

## Features

- **Unbeatable AI**: Uses minimax algorithm with alpha-beta pruning
- **Dynamic Messages**: AI-generated win/lose/draw messages using Claude Sonnet 4
- **Single File**: Complete game in one HTML file with embedded CSS/JS
- **Responsive Design**: Works on desktop and mobile devices
- **CORS Solutions**: Multiple proxy fallbacks for API calls
- **Modern UI**: Clean design with animations and visual feedback

## How to Play

1. Open `tic-tac-toe.html` in your web browser
2. (Optional) Enter your Claude API key for AI-generated messages
3. Click any cell to make your move as X
4. Try to beat the unbeatable AI playing as O!

## Technical Details

- Pure HTML/CSS/JavaScript - no dependencies
- Minimax algorithm ensures AI never loses
- CORS proxy fallbacks handle API restrictions
- LocalStorage persistence for API keys
- Graceful error handling with message fallbacks

## API Integration

The game uses the Anthropic API to generate contextual end messages. Without an API key, it falls back to standard emoji messages.

Built with Claude Code 🤖