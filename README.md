# 🚀 Marketing Crew

## Introduction
**Marketing Crew** is an **agentic AI system** designed to collaboratively create engaging social media content. It simulates a full marketing team—complete with a Head of Marketing, Creative Content Creator, Content Writer, and SEO Specialist—working together to produce optimized posts for various platforms.

Built using the **CrewAI framework**, this project demonstrates how autonomous AI agents can be orchestrated to handle creative, analytical, and strategic marketing tasks efficiently.

---

## 📋 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Architecture](#architecture)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Example Output](#example-output)
- [Contributing](#contributing)
- [License](#license)

---

## 🌟 Features
- 🧠 Multi-agent marketing team simulation  
- ✍️ Automated social media post creation  
- 🔍 SEO optimization suggestions  
- 🎨 Content ideation via a Creative Writer agent  
- 🧩 Modular and easily extendable design  
- ⚙️ Built with **CrewAI** for seamless agent orchestration  

---

## 🏗️ Architecture
The **Marketing Crew** consists of the following autonomous agents:

| Role | Description |
|------|--------------|
| **Head of Marketing** | Coordinates the crew and defines goals |
| **Creative Content Creator** | Generates fresh and engaging content ideas |
| **Content Writer** | Writes polished and platform-specific content |
| **SEO Specialist** | Optimizes posts for visibility and engagement |

All agents communicate through the **CrewAI** framework, passing context, ideas, and drafts between one another.

---

## 💻 Requirements

- Python 3.10 or higher  
- `crewai` library (for agent orchestration)  
- Additional libraries (listed in `requirements.txt` if available)

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/ashdrift231/marketing_crew.git
cd marketing_crew

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the main crew script:

```bash
python crew.py
```

The crew will collaboratively generate a marketing plan or social media post draft.  
You can modify prompts, goals, or agent behavior through the configuration files.

---

## 🧩 Configuration

Configuration files are stored under the `config/` directory.  
Typical parameters include:

- Agent roles and descriptions  
- Goals and prompts  
- Output directories (e.g. `resources/saved_drafts/`)  
- Platform or brand-specific settings  

To customize behavior, edit the config files or modify agent definitions inside `crew.py`.

---

## 📁 Project Structure

```
marketing_crew/
├── config/                  # Configuration files for crew and agents
├── resources/
│   └── saved_drafts/        # Generated social media drafts and outputs
├── crew.py                  # Main script defining and running the crew
└── README.md                # Project documentation
```

---

## ✨ Example Output

Example generated draft:

```
Platform: LinkedIn  
Goal: Promote new product launch

🎯 Draft:
"Introducing our latest innovation in AI-driven analytics — smarter insights, faster decisions. Join us in redefining data intelligence. #AI #Innovation #DataDriven"
```

---

## 🤝 Contributing

Contributions are welcome!  
If you’d like to improve the crew logic, add new agent roles, or enhance post-generation quality:

1. Fork the repo  
2. Create a new branch (`feature/new-agent`)  
3. Commit changes  
4. Submit a pull request  

---

---

### 🧠 Built With
- [CrewAI](https://github.com/joaomdmoura/crewai)
- Python 3.10+
- OpenAI / LLM backends (depending on config)
