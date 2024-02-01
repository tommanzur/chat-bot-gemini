# ChatBot: A Conversational AI Chatbot

Welcome to the GitHub repository of ChatBot, an AI-powered chatbot designed to deliver an interactive and engaging conversational experience. Built using JavaScript and integrating Google's Generative AI, ChatBot is a modern chat application that showcases cutting-edge technology in natural language processing and user interaction.

## Features

- **AI-Powered Responses**: Utilizes Google Generative AI's Gemini-Pro model for generating coherent and contextually relevant responses.
- **User-Friendly Interface**: A clean and intuitive chat interface, ensuring a seamless user experience.
- **History Tracking**: Maintains a conversation history for context retention and improved chat continuity.
- **Markdown Support**: Responses are rendered using markdown for enhanced readability and formatting.

## ChatBot Interface Overview

![ChatBot User Interface](public/Chatbot.png)

The above image illustrates the user interface of ChatBot. Our chatbot integrates the latest in conversational AI to provide a smooth and natural chatting experience. The interface is designed to be simple and user-friendly, making it easy for users to start chatting with ChatBot right away. With the integration of the Gemini-Pro model from Google Generative AI, users can expect high-quality, coherent, and context-aware conversations.


## Installation and Setup

1. **Clone the Repository**
```bash
git clone [repository-url]
```

2. **Install Dependencies**
Navigate to the project directory and install the required dependencies:

3. **Install Required Libraries**
Install Google Generative AI and markdown-it libraries:
```bash
npm install @google/generative-ai markdown-it
```

4. **Environment Variables**
Set up the `.env` file with your Google Generative AI API Key:
```bash
VITE_API_KEY=your_api_key_here
```

5. **Run the Application**
Start the application locally:
```bash
npm run dev
```

6. **Open in Browser**
The chatbot will be available at `http://localhost:3000` (default URL).

## Usage

- Type your message in the text area at the bottom of the chat interface.
- Press 'Send' or Enter to submit your message.
- The chatbot will respond promptly, with responses displayed in the chat area.
