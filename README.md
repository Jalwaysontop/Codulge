# Codulge
Codulge is a Code Reviewer built with a **C++ backend**. It allows developers to submit code snippets and receive instant, high-quality suggestions, bug fixes, and detailed logical explanations powered by the **Google Gemini API**.

## 🚀 The Mission
While most AI tools are built on high-level languages, Codulge utilizes **C++** to demonstrate that AI orchestration can be handled with system-level efficiency, providing a robust foundation for high-performance developer tools.

## ✨ Key Features
* **Automated Code Review:** Submits code snippets to Gemini for deep structural analysis.
* **Smart Corrections:** Receives "best-practice" code rewrites to improve efficiency and readability.
* **Detailed Explanations:** Breaks down complex logic into easy-to-understand explanations for better learning.
* **System-Level Performance:** Uses a compiled C++ backend to handle API requests with minimal overhead.
* **Containerized Workflow:** Fully integrated with Docker for consistent development and deployment.

## 🛠️ Technical Stack
* **Backend:** C++ (98.9% of codebase)
* **AI Model:** Google Gemini API
* **Networking:** `cpp-httplib` (Header-only C++ HTTP library)
* **Data Parsing:** `nlohmann/json` for structured JSON handling
* **Frontend:** HTML5/CSS3
* **DevOps:** Docker

## 🏗️ How it Works
1. **Submit:** User pastes a code snippet into the web interface.
2. **Process:** The C++ server wraps the code in a specialized "Code Reviewer" prompt.
3. **Analyze:** The Gemini API analyzes the code for bugs, logic errors, and optimization opportunities.
4. **Respond:** The backend parses the AI's JSON response and displays the **Corrected Code** and **Explanations** side-by-side.

## ⚙️ Installation & Usage

### Prerequisites
* Docker
* Gemini API Key from [Google AI Studio](https://aistudio.google.com/)
