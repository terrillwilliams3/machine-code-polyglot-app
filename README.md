Machine Code Polyglot

A cyberpunk-themed, real-time code translation interface powered by the Gemini API.

⚡ Overview

Machine Code Polyglot is a single-page web application that allows developers to write code in one language and instantly see it translated into eight other programming languages simultaneously.

Designed with a gritty Maelstrom/Cyberpunk aesthetic, the interface features glitch effects, neon visuals, and a terminal-like user experience.

🚀 Features

Multi-Language Support: Instantly translates between C, C++, Python, Go, Rust, JavaScript, Java, HTML, and CSS.

Real-Time Translation: Uses a debounce timer to trigger translations automatically as you type.

Gemini AI Powered: Leverages Google's Gemini API for accurate and context-aware code conversion.

Cyberpunk UI: Custom CSS animations, glitch text effects, and a responsive grid layout styled with Tailwind CSS.

Single File Architecture: The entire app runs from a single HTML file—no build steps or complex backend required.

Data Extraction: Download translated code files directly with a single click (.py, .c, .js, etc.).

System Telemetry: Real-time monitoring footer displays API latency (ms) and estimated token usage.

Smart Editor: Includes line numbering and auto-indentation awareness for a comfortable coding experience.

🛠️ Technologies Used

Core: HTML5, JavaScript (ES6+)

Styling: Tailwind CSS (via CDN), Custom CSS Animations

Icons: Font Awesome

Fonts: Share Tech Mono (Google Fonts)

AI Backend: Google Gemini API (via REST)

📦 Installation & Setup

Since this is a client-side application, no installation or package manager (npm/pip) is required.

Clone the repository-

Open the application-

Navigate to the project folder-

Open index.html in any modern web browser.

Pro Tip: In VS Code, use the "Live Server" extension for the best experience.

🎮 How to Use

Get an API Key: You need a free API key from Google AI Studio.

Enter Credentials: Paste your API key into the input field at the top right of the app.

Select Protocol: Choose your input language (e.g., Python) from the dropdown menu. The selected language will automatically shift to the first slot in the grid.

Write Code: Type your code in the active window (marked with a red border).

Watch it Happen: After a short pause (1.5 seconds), the Polyglot System Status will activate, and the translation engine will populate the other 8 windows.

Reset: Use the RESET button in the header to clear all input and output fields instantly.

Download: Click the download icon 📥 on any code window to save that specific snippet as a file.

⚠️ Note on Security

This application runs entirely in your browser. Your API key is sent directly from your browser to Google's servers. It is never stored on any other server or backend.

👤 Author:

LinkedIn: https://www.linkedin.com/in/Terrill-Williams-Verified/

GitHub: @terrillwilliams3

📄 License

This project is open source and available under the MIT License.