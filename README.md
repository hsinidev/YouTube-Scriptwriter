# 🎬 YouTube Scriptwriter – B-Roll Automation

A **powerful, dynamically-themed desktop application** designed for video creators.  
It automates the **scriptwriting process** by taking a title and outline, then instantly generating a **fully structured, time-stamped video script** with separate tracks for **Narration** and **B-Roll/Visual Action**.

---

## 📸 Overview

**YouTube Scriptwriter** is built for creators who want to speed up content production without sacrificing structure or creativity.  
Simply provide your **video title** and **outline**, and the app generates:

- 🗣️ **Narration track** – polished and ready to record  
- 🎥 **B-Roll/Action track** – perfectly aligned visuals  
- ⏱️ **Timestamps** – estimated for smooth pacing and video timing  

<!-- Placeholder for a screenshot -->
*(Screenshot coming soon)*

---

## ✨ Features

- **Structured Output**  
  Generates a clear, unified script separating **NARRATION** and **B-ROLL/ACTION** cues.

- **Time-Stamped Segments**  
  Automatically includes estimated timestamps for each segment, helping you hit your target duration (e.g., 5 minutes).

- **Flexible AI Power**  
  Switch between **Ollama Local** (for privacy and speed) and **Ollama Cloud** (for powerful remote models).

- **Dynamic Theming**  
  Multiple unique color schemes and **Dark/Light mode** options.

- **Native Text Controls**  
  Includes right-click **Cut / Copy / Paste** context menus across all text fields.

---

## 🧰 Tech Stack

| Component   | Technology Used     |
|--------------|--------------------|
| **Frontend** | CustomTkinter      |
| **Language** | Python             |
| **AI Engine** | Ollama (Local/Cloud) |

---

## 🚀 Getting Started

Follow these steps to set up and run **YouTube Scriptwriter** on your local Windows PC.

### 🔧 Prerequisites

Make sure you have the following installed:

- [Python 3.11 or 3.12](https://www.python.org/downloads/)  
  *(Check "Add python.exe to PATH" during installation)*
- [Git for Windows](https://git-scm.com/download/win)
- [Ollama](https://ollama.ai/)  
  Then download a model (example):  
  ```bash
  ollama pull llama3:8b



  📦 Installation


  # Clone the repository
git clone https://github.com/hsinidev/youtube-scriptwriter-ai.git

# Navigate to the project folder
cd youtube-scriptwriter-ai

# (Optional) Create and activate a virtual environment
python -m venv .venv
.venv\Scripts\activate

# Install dependencies
pip install customtkinter ollama

▶️ Running the Application


python scriptwriter_app.py



🗂️ Project Structure


/
├── .venv/                     # Python virtual environment
├── scriptwriter_app.py        # Main application entry point
├── master_themes.json         # Defines all color themes
├── magic_theme_youtube.json   # Defines the 'Video Teal' theme
├── scriptwriter_settings.json # User settings (generated at runtime)
└── README.md                  # Project documentation


🧑‍💻 Developer Notes

The app dynamically updates the theme without restart.

Timestamps are automatically generated based on target duration and content pacing.

Ollama integration allows you to swap models or endpoints seamlessly.

📄 License

This project is licensed under the MIT License.
See the LICENSE
 file for details.

👨‍💻 Author

Developed by Hsini Mohamed

💡 "Designed to empower creators through intelligent automation."



---

Would you like me to add **badges** (Python version, license, last commit, etc.) and a **preview image placeholder** for GitHub visual polish?


