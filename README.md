# 🐍 Python Project Trio

<p align="center">
  <img src="https://img.shields.io/badge/Python-Projects-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Projects">
  <img src="https://img.shields.io/badge/AI%20%26%20ML-Projects-FF6F00?style=for-the-badge" alt="AI & ML">
  <img src="https://img.shields.io/badge/NLP-Chatbot-4B8BBE?style=for-the-badge" alt="NLP">
  <img src="https://img.shields.io/badge/Minimax-Game%20AI-6A1B9A?style=for-the-badge" alt="Minimax">
  <img src="https://img.shields.io/badge/TMDb-API-01D277?style=for-the-badge" alt="TMDb API">
</p>

<p align="center">
  <b>Three Python projects exploring conversational AI, game algorithms, and recommendation systems.</b>
</p>

<p align="center">
  <a href="#-projects">Projects</a> •
  <a href="#-technologies">Technologies</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-project-highlights">Highlights</a>
</p>

---

## ✨ Overview

**Python Project Trio** is a collection of three independent Python projects built to explore different areas of programming, Artificial Intelligence, Natural Language Processing, algorithms, and data-driven applications.

The repository contains:

| Project | Focus | Core Concept |
|---|---|---|
| 💬 **Chatbot** | Conversational AI | Natural Language Processing |
| 🎮 **Tic-Tac-Toe with AI** | Game AI | Minimax Algorithm |
| 🎬 **Movie Recommendation System** | Recommendation | User Preferences & TMDb API |

Together, these projects demonstrate different approaches to building interactive Python applications — from language-based interaction to algorithmic decision-making and personalized recommendations.

---

# 🚀 Projects

## 💬 1. Chatbot

### 🧠 Conversational Python Assistant

A Python-based chatbot designed to interact with users through natural language and respond to a variety of queries.

### ✨ Features

- 💬 Interactive conversational interface
- 🧠 Natural Language Processing capabilities
- 🔎 Handles a variety of user queries
- 🐍 Built with Python
- ⚡ Simple and lightweight interaction model

### 🛠️ Technologies

- Python
- Natural Language Processing
- NLTK
- spaCy

---

## 🎮 2. Tic-Tac-Toe with AI

### 🤖 Play Against an AI Opponent

A console-based Tic-Tac-Toe implementation where a human player competes against an AI opponent using the **Minimax algorithm**.

The project demonstrates how an AI can evaluate possible game states and select moves based on optimal decision-making.

### ✨ Features

- 🤖 AI opponent powered by Minimax
- 🧠 Optimal move selection
- 🎮 Human vs AI gameplay
- 🖥️ Simple console interface
- 🏆 Supports Win / Lose / Draw outcomes

### 🧩 Core Concept

```text
Current Game State
        │
        ▼
Generate Possible Moves
        │
        ▼
Evaluate Future States
        │
        ▼
Minimax Algorithm
        │
        ▼
Select Best Move
        │
        ▼
Continue Game
```

### 🛠️ Technologies

- Python
- Minimax Algorithm
- Game State Evaluation

---

## 🎬 3. Movie Recommendation System

### 🍿 Personalized Movie Discovery

A Python-based movie recommendation system that uses user preferences and ratings to suggest movies and integrates with the **TMDb API** to retrieve movie information.

### ✨ Features

- 🎬 Movie recommendations based on preferences and ratings
- ⭐ User rating-based recommendations
- 🔎 Popular movie retrieval through TMDb
- 📡 API integration for movie information
- 📊 Data processing using Pandas
- 🧠 Recommendation logic using Scikit-learn

### 🔄 Workflow

```text
User Preferences / Ratings
          │
          ▼
     Data Processing
          │
          ▼
 Recommendation Logic
          │
          ▼
    Movie Selection
          │
          ▼
      TMDb API
          │
          ▼
 Movie Information
```

### 🛠️ Technologies

- Python
- Pandas
- Scikit-learn
- Requests
- TMDb API

---

# 🧰 Technologies

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
<img src="https://img.shields.io/badge/NLTK-154F5B?style=flat-square" alt="NLTK">
<img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square" alt="spaCy">
<img src="https://img.shields.io/badge/TMDb%20API-01D277?style=flat-square" alt="TMDb API">

</p>

---

# 📊 Project Highlights

| 💡 Area | 🧪 Implementation |
|---|---|
| 🐍 Python | Core development language |
| 🧠 NLP | Chatbot interaction |
| 🤖 Game AI | Minimax-based Tic-Tac-Toe |
| 🎬 Recommendations | Movie preference-based suggestions |
| 📡 API Integration | TMDb movie data |
| 📊 Data Processing | Pandas |
| 🔬 Machine Learning | Scikit-learn |

---

# ⚙️ Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Divakar1326/Python-Project-Trio.git
cd Python-Project-Trio
```

## 2️⃣ Install Dependencies

If a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

Otherwise, install the dependencies required by the individual project you want to run.

## 3️⃣ Choose a Project

Navigate to the corresponding project file and run it using Python.

```bash
python <project-file>.py
```

---

# 🔑 TMDb API Setup

The **Movie Recommendation System** requires a TMDb API key.

1. Create a TMDb account.
2. Generate an API key.
3. Add the API key to the project configuration.
4. Run the recommendation system.

> ⚠️ Never commit your API key directly to a public repository. Use environment variables or a local configuration file.

---

# 📁 Repository Structure

```text
Python-Project-Trio/
│
├── 💬 ChatBot
├── 🎮 Tic-Tac-Toe with AI
├── 🎬 Movie Recommendation System
└── 📄 README.md
```

> The exact filenames may vary depending on the current repository structure.

---

# 🎯 What This Repository Demonstrates

This project collection explores three different problem-solving approaches:

### 💬 Natural Language Processing

Building an interactive application capable of processing and responding to user queries.

### 🤖 Algorithmic Decision Making

Using the Minimax algorithm to create an AI opponent capable of evaluating possible game states.

### 🎬 Recommendation Systems

Combining user preferences, data processing, recommendation logic, and external API integration to build a movie discovery application.

---

# 🌱 Learning Focus

These projects were developed as practical implementations of Python programming, Artificial Intelligence concepts, algorithms, Natural Language Processing, data processing, and API integration.

The goal was to move beyond isolated exercises and build **working applications around different technical concepts**.

---

# 🔮 Future Improvements

Potential directions for extending the projects include:

- 💬 Improve chatbot conversation capabilities
- 🎮 Add different Tic-Tac-Toe difficulty levels
- 🎬 Enhance recommendation quality
- 📊 Add richer movie filtering
- 🖥️ Build graphical/web interfaces
- 🔐 Move API credentials to environment variables
- 🧪 Add automated testing

---

# 👨‍💻 Author

## Divakar M

**B.Tech CSE (Artificial Intelligence & Data Science)**

AI/ML • Generative AI • Python • Machine Learning

<p align="center">
  <a href="https://github.com/Divakar1326">
    <img src="https://img.shields.io/badge/GitHub-Divakar1326-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

---

<p align="center">
  ⭐ If you find this project collection useful, consider starring the repository.
</p>

<p align="center">
  <b>Built with Python 🐍 • Learned by Building 🚀</b>
</p>
