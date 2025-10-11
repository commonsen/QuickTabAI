# 🧠 QuickTab AI – Fast, Lightweight Desktop AI Assistant

QuickTab AI is a C# WPF-based desktop assistant designed for speed, simplicity, and ease of use.  
It connects to the Groq API (LLaMA 3.1 model) to provide real-time, concise AI responses directly inside a clean Windows interface.  

This project focuses on creating an efficient, local-friendly AI experience without requiring heavy frameworks or web apps.

## ⚙️ Key Features
- 💬 **Interactive Chat UI** – simple, scrollable chat interface built with WPF
- ⚡ **Real-Time AI Responses** – integrates with the Groq API for fast output
- 🧩 **Persistent System Memory** – stores AI personality/configuration in a JSON file (`qt_config.json`)
- 🧠 **Smart Context Handling** – retains conversation history (auto-resets after 20 turns for performance)
- 🔄 **Retry & Backoff Logic** – gracefully handles API timeouts and network issues
- 🖥️ **Lightweight Desktop Build** – minimal dependencies and smooth UI
- 🔒 **Configurable System Prompt** – define how the AI behaves or responds via persistent settings

## 🏗️ Built With
- **Language:** C# (.NET 6.0)
- **Framework:** WPF (Windows Presentation Foundation)
- **API:** Groq LLaMA 3.1 (via HTTP POST requests)
- **Tools:** Visual Studio Community Edition

## Downloading The Program
- **GoTo** - Go to my Release section to download the initial program(https://github.com/commonsen/QuickTabAI/releases)
- **Note** - Files are under Testing and not to be used commercially.
