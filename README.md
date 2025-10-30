# VaishnaviParab-assigment-solution
# Entity Extraction from Conversations System

<div align="center">

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-flat&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-flat&logo=python&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-00FF00?style=for-flat&logo=groq&logoColor=black)
![AI](https://img.shields.io/badge/AI-Powered-FF6B6B?style=for-flat)
![License](https://img.shields.io/badge/License-MIT-green?style=for-flat)





</div>

<div align="center">
  <img src="https://via.placeholder.com/800x400/4F46E5/FFFFFF?text=Entity+Extraction+System+Dashboard" alt="Dashboard Preview" width="800"/>
</div>

## Features

###  Smart Entity Extraction
| Entity Type | Description | Examples |
|-------------|-------------|----------|
| **People** | Full names of individuals mentioned | "Sarah", "Dr. Smith", "Alex Johnson" |
| ** Topics** | Technologies, frameworks, subjects | "Python", "React", "Machine Learning" |
| ** Preferences** | Likes, dislikes, goals, inclinations | Learning goals, technology preferences |
| ** Facts** | Concrete statements and achievements | Companies, locations, skills, roles |

### Real-time Processing
- ** Lightning Fast**: Powered by Groq's LPU technology
- ** Live Analytics**: Real-time processing metrics and statistics
- ** Beautiful UI**: Center-aligned, professional Streamlit interface

### 💾 Data Management
- **📥 JSON Export**: Download individual results or complete history
- **📈 Progress Tracking**: Monitor extraction performance over time
- **🔍 Raw Data Access**: Full JSON output for developers

---

## 🛠️ Technical Details

### 🤖 AI-Powered Engine

<div align="center">

| Component | Specification |
|-----------|---------------|
| **Model** | `llama-3.1-8b-instant` |
| **Provider** | Groq AI |
| **Temperature** | 0.1 (for consistent results) |
| **Max Tokens** | 1024 |
| **Speed** | ⚡ Ultra-fast inference |

</div>

### 🔧 Extraction Logic

```python
# Advanced Prompt Engineering
def extract_entities(conversation):
    """
    Sophisticated entity categorization:
    - People: Full names with context awareness
    - Topics: Tech stack, frameworks, languages
    - Preferences: Categorized preferences and goals
    - Facts: Typed factual information
    """
