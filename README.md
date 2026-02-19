# **React AI ChatBot 🤖**

A modern, responsive AI Chat application built with React and powered by Google Gemini API. This project features a clean UI, real-time message streaming, and a persistent chat history.

## **🚀 Features**
Gemini AI Integration: Real-time conversations with Google's Gemini-2.0-Flash model.

Debounced Inputs: Optimized API calls to prevent rate-limiting (429 errors).

Recent Search History: Sidebar to track and revisit previous queries.

Dark/Light Mode: Styled with a modern aesthetic.

Responsive Design: Works on desktops, tablets, and mobile devices.

## **🛠️ Tech Stack**
Frontend: React.js

Styling: CSS3 (with Flexbox/Grid)

API: Google Generative AI (Gemini API)

Icons: Lucide React (or FontAwesome)

Build Tool: Vite

## **⚙️ Getting Started**
Prerequisites
Node.js installed

A Gemini API Key (Get one at [Google AI Studio](https://aistudio.google.com/))

1. Installation
Clone the repo:

``git clone https://github.com/anshG2003/React-AI-chatBot.git``

``cd React-AI-chatBot``

## 2. Install dependencies ##

``npm install``

## 3. Environment Setup
Create a .env file in the root directory and add your API key:

``VITE_GEMINI_API_KEY=your_api_key_here``

## 4. Run the development server

``npm run dev``

## 📝 Troubleshooting
> 429 Too Many Requests: This project implements debouncing to stay within the free tier limits (15 RPM).

> Missing "dev" script: Ensure you have "dev": "vite" inside the scripts section of your package.json.

> Key Prop Warning: All list items in the Recent Search sidebar use unique IDs to ensure efficient React rendering.

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

Built with ❤️ by Ansh
