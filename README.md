# AI Chat Assistant

A modern chat interface featuring an AI assistant that responds with dynamic emoji expressions based on the conversation's emotional tone. The application includes dark/light theme support and a clean, responsive design for an engaging user experience.

## Features

- 🎭 **Emotional Response System**: The AI assistant's emoji changes based on the conversation tone
- 🌓 **Dark/Light Theme**: Toggle between dark and light modes
- 💬 **Real-time Chat**: Instant message responses from the AI
- 🎨 **Modern UI**: Clean and responsive design

## Emotional States

The AI assistant has four emotional states:

- 😊 **Happy**: Responds to positive messages and successful interactions
- 🤔 **Thinking**: Shows when processing questions or complex queries
- 😔 **Sad**: Appears during errors or negative situations
- 😠 **Angry**: Reacts to frustrating or negative content

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- JavaScript (Vanilla)
- Node.js (Backend)

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file with your API key
4. Start the server:
   ```bash
   node server.js
   ```
5. Open `index.html` in your browser

## Environment Variables

Create a `.env` file in the root directory and add your API key:
```
OPENAI_API_KEY=your_api_key_here
```

## Usage Examples

Happy Response:
```
User: "Thank you, that's great!"
AI: 😊 *responds with happy expression*
```

Thinking State:
```
User: "How does this work?"
AI: 🤔 *shows thinking expression while processing*
```

## License

MIT License - feel free to use this project for your own purposes! 