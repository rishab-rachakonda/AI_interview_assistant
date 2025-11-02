# 🤖 AI Interview Assistant

An interactive **AI-powered interview preparation app** built with **Streamlit**.  
The app dynamically generates interview questions based on user-selected skills, role, and difficulty level — helping users prepare for real-world technical interviews efficiently.

---

## 🚀 Features

- 🎯 **Skill-Based Question Generation** – Enter any skill (e.g., Python, SQL, Flutter) to get tailored interview questions.  
- 💼 **Role Customization** – Generate questions specific to software roles like SDE, ML Engineer, or Data Scientist.  
- ⚙️ **Difficulty Levels** – Choose between *Easy*, *Medium*, and *Hard* modes for progressive learning.  
- 💬 **Interactive UI** – Simple and clean Streamlit interface for smooth user experience.  
- 🧠 **Expandable Architecture** – Easily plug in new models or APIs (OpenAI, Ollama, etc.) in `utils/question_generator.py`.

---

## 🗂️ Project Structure

ai_interview_asst/
│
├── assets/ # Images, icons, or supporting files
├── examples/ # Sample inputs or demonstrations
├── utils/ # Utility scripts (question generation, model handlers)
│ └── question_generator.py
│
├── app.py # Main Streamlit application
├── config.py # Configuration file for API keys, settings, etc.
├── requirements.txt # Python dependencies
└── README.md # Project documentation



---

## 🧩 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/rishab-rachakonda/AI_interview_assistant.git
   cd ai_interview_asst


# Create a virtual environment


python -m venv env
env\Scripts\activate     # On Windows
# or
source env/bin/activate  # On Mac/Linux

# Install dependencies

pip install -r requirements.txt
# Run the Streamlit app

streamlit run app.py



🧠 How It Works
User inputs skills, role, and difficulty.

The app calls generate_questions() in utils/question_generator.py.

Questions are fetched/generated via a local LLM or API (e.g., OpenAI/Ollama).

The output is displayed interactively using Streamlit components.

🧾 Requirements
Python 3.10+

Streamlit

OpenAI SDK (if used)

dotenv (for environment variables)

🧑‍💻 Future Improvements
✅ Add voice-based mock interviews

✅ Save user performance analytics

✅ Integrate more LLM backends (Claude, Gemini, etc.)

✅ Export questions and answers as PDF

📄 License
This project is licensed under the MIT License — feel free to use and modify.

Created with ❤️ by Rishab Rachakonda# 🤖 AI Interview Assistant

An interactive **AI-powered interview preparation app** built with **Streamlit**.  
The app dynamically generates interview questions based on user-selected skills, role, and difficulty level — helping users prepare for real-world technical interviews efficiently.

---

## 🚀 Features

- 🎯 **Skill-Based Question Generation** – Enter any skill (e.g., Python, SQL, Flutter) to get tailored interview questions.  
- 💼 **Role Customization** – Generate questions specific to software roles like SDE, ML Engineer, or Data Scientist.  
- ⚙️ **Difficulty Levels** – Choose between *Easy*, *Medium*, and *Hard* modes for progressive learning.  
- 💬 **Interactive UI** – Simple and clean Streamlit interface for smooth user experience.  
- 🧠 **Expandable Architecture** – Easily plug in new models or APIs (OpenAI, Ollama, etc.) in `utils/question_generator.py`.

---

## 🗂️ Project Structure

ai_interview_asst/
│
├── assets/ # Images, icons, or supporting files
├── examples/ # Sample inputs or demonstrations
├── utils/ # Utility scripts (question generation, model handlers)
│ └── question_generator.py
│
├── app.py # Main Streamlit application
├── config.py # Configuration file for API keys, settings, etc.
├── requirements.txt # Python dependencies
└── README.md # Project documentation



---

## 🧩 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/rishab-rachakonda/AI_interview_assistant.git
   cd ai_interview_asst


# Create a virtual environment


python -m venv env
env\Scripts\activate     # On Windows
# or
source env/bin/activate  # On Mac/Linux

# Install dependencies

pip install -r requirements.txt
# Run the Streamlit app

streamlit run app.py



🧠 How It Works
User inputs skills, role, and difficulty.

The app calls generate_questions() in utils/question_generator.py.

Questions are fetched/generated via a local LLM or API (e.g., OpenAI/Ollama).

The output is displayed interactively using Streamlit components.

🧾 Requirements
Python 3.10+

Streamlit

OpenAI SDK (if used)

dotenv (for environment variables)

🧑‍💻 Future Improvements
✅ Add voice-based mock interviews

✅ Save user performance analytics

✅ Integrate more LLM backends (Claude, Gemini, etc.)

✅ Export questions and answers as PDF

📄 License
This project is licensed under the MIT License — feel free to use and modify.

Created with ❤️ by Rishab Rachakonda
