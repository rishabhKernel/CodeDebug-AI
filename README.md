# CodeDebug AI

CodeDebug AI is an intelligent code debugging assistant designed to help developers find, analyze, and fix errors in their code instantly. With a user-friendly interface, it allows users to paste their code, identify potential issues, and get corrected solutions accompanied by best practices. 

The demo interface uses the **Gemini 2.0 Flash API** to dynamically analyze user-provided code in various languages (JavaScript, HTML, CSS, Python, Java, C#, C++).

## 🚀 Features

- **Multi-Language Support**: Debug JavaScript, HTML, CSS, Python, Java, C#, and C++.
- **AI-Powered Code Analysis**: Leverages Google's Gemini API to detect syntax and logical errors and explain fixes.
- **Interactive Chat Interface**: Engaging, chat-like UI mimicking real-time assistance with typing indicators.
- **Responsive Design**: Built using Tailwind CSS, ensuring smooth operation across mobile and desktop devices.
- **Syntax Highlighting**: Code snippets are presented clearly with helpful formatting.

## 📁 File Structure

- `index.html`: The main landing page with project details and a simulated chatbot demo for unauthenticated visitors.
- `index1.html`: The actual functioning chat interface integrating the Gemini API to analyze user code.
- `main.js`: Contains logic for mobile navigation and a simulated, delay-based chat demo on the landing page.
- `about.html`: Information about the project.
- `auth.html`: User login and registration interface.
- `auth.js`: Front-end mock validation and simple page-toggle logic for authentication actions.
- `privacy_Policy.html`: Details regarding user privacy and data security.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla), Tailwind CSS
- **Icons**: FontAwesome 
- **AI Integration**: Google Gemini API (v1beta, gemini-2.0-flash)

## 💻 Getting Started

### Prerequisites

You need a modern web browser to view the application and a local web server extension (e.g., Live Server for VS Code) to serve the files properly.

### Running Locally

1. **Clone the repository** (if not already downloaded)
   ```bash
   git clone <repository-url>
   ```

2. **Open the project foldering**
   ```bash
   cd CodeDebug-AI-main
   ```

3. **Set up Gemini API Key**
   - Open `index1.html`
   - Locate the `API_KEY` constant around line 210:
     ```javascript
     const API_KEY = 'YOUR_GEMINI_API_KEY_HERE';
     ```
   - Replace the key with your own Google Gemini API Key. To get a key, visit [Google AI Studio](https://aistudio.google.com/).
   - *Note*: Ensure you restrict API key usage or move it to a backend service in a production environment.

4. **Launch the app**
   - Open `index.html` in your browser to view the landing page.
   - Click "See Demo" or open `index1.html` directly to interact with the fully functioning AI debugging assistant.

## 📝 Usage

1. Select your target programming language from the dropdown in the chat input area.
2. Paste the portion of your code containing errors or bugs into the chat box.
3. Include any error messages you received to help the AI better analyze the issue.
4. Hit "Send" and await the corrected code and explanation!

## 📄 License

© 2023 CodeDebug AI. All rights reserved.