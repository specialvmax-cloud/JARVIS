JARVIS Core — Prototype 01
Mobile-friendly personal AI assistant prototype using Gemini and Groq APIs. Keys, chats, tasks, and memories are saved in the current browser's local storage.\n
Features
Gemini / Groq chat
Multiple API keys per provider with basic rotation when requests fail
Local chat history, tasks, and personal memory
Text/code file reading and AI analysis
Responsive UI
Run
Open index.html in a browser, then visit Settings & keys to add your API keys.\n
Important security warning
This prototype makes provider API requests directly from the browser. Keys saved in local storage are not encrypted and can be inspected by anyone with access to that browser/device. Do not use it on a shared device or publish it as a public app with your keys entered. A backend proxy with authentication should be added before public deployment.
Key sources
Gemini API key: Google AI Studio
Groq API key: Groq developer console
Tavily search key: Tavily developer console (search key field is reserved; research integration will be completed in a subsequent build)
