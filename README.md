# PROG6221POE_PART-2
# 🛡️ Cybersecurity Awareness Chatbot (Part 2 — GUI Application)

An interactive, user-friendly desktop GUI chatbot built with C# (.NET 8.0) and WPF/WinForms. Designed to educate users on essential cybersecurity topics through keyword recognition, sentiment detection, memory recall, and dynamic conversational flows.

---

## 📌 Features & Functional Requirements

- **🎨 Graphical User Interface (WPF/WinForms):** Modern desktop UI with styled banners, clear typography, and responsive controls.
- **🎙️ Voice Greeting Integration:** Plays an audio greeting (`.wav`) upon startup.
- **🔍 Keyword Recognition:** Identifies core cybersecurity topics (e.g., `password`, `scam`, `privacy`, `phishing`).
- **🎲 Dynamic & Random Responses:** Uses C# collections/lists to randomly serve cybersecurity tips and advice.
- **💬 Natural Conversation Flow:** Supports follow-up prompts (`explain more`, `give me another tip`) without resetting context.
- **🧠 Memory & Recall:** Stores user preferences (e.g., user's name, preferred security topic) and recalls them later in conversation.
- **💙 Sentiment Detection:** Recognizes user emotional states (`worried`, `curious`, `frustrated`) and adapts responses with empathetic messaging.
- **🛡️ Robust Error Handling:** Graceful fallback handling for unrecognized input without system crashes.

---

## 🛠️ Architecture & Code Optimisation

- **Data Structures:** Uses C# `List<T>`, `Dictionary<TKey, TValue>`, and Arrays for efficient lookup and response management.
- **OOP Design:** Modular class structures separating UI logic, response engines, memory stores, and audio handlers.
- **Delegates & Events:** Implemented C# delegates for event-driven UI updates and response handling.

---

## 📸 Screenshots & Workflow

### 1. Main Chat Interface
![Main Interface](screenshots/gui-main-interface.png)
*Figure 1: Main GUI window displaying ASCII banner, user greeting, and chat window.*

### 2. Conversation & Sentiment Detection
![Sentiment & Memory](screenshots/gui-sentiment-memory.png)
*Figure 2: Chatbot detecting user sentiment and recalling saved preferences.*

### 3. Application Workflow Diagram
![Workflow Diagram](screenshots/workflow-diagram.png)
*Figure 3: High-level architectural flowchart of input handling, keyword matching, memory store, and output formatting.*

---

## 📹 Presentation Video & Links

- **YouTube Video Walkthrough (Unlisted):** [Watch Video Presentation](https://youtu.be/YOUR_UNLISTED_VIDEO_ID)
- **GitHub Repository:** [View Repository](https://github.com/YOUR_GITHUB_USERNAME/Cybersecurity-Awareness-Chatbot)

---

## ⚙️ Running the Project

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/Cybersecurity-Awareness-Chatbot.git](https://github.com/YOUR_GITHUB_USERNAME/Cybersecurity-Awareness-Chatbot.git)
