# Capstone — File Integrity Monitoring (FIM) Agent

This repository contains a **Python-based File Integrity Monitoring (FIM) Agent** developed as a capstone project.  
The goal of the project is to monitor selected files and directories for changes such as creation, deletion, and modification, and to log these events for security and auditing purposes.

The project includes both **backend logic (Python)** and **supporting components (e.g., configuration, logs, tests, and documentation)**.

---

## Features

- File and directory integrity monitoring (FIM)
- Detection of file changes (create, modify, delete)
- Configurable monitoring paths
- Event logging for auditing and analysis
- Modular project structure
- Automated tests

---

## Project Structure

Capstone/
│
├── fim_agent/ # Core FIM agent source code
├── config/ # Configuration files
├── watched/ # Sample directory being monitored
├── logs/ # Log output files
├── data/ # Project-related data
├── staging/ # Staging / development environment
├── tests/ # Unit and integration tests
├── docs/ # Documentation
├── requirements.txt # Python dependencies
└── README.md


---

## Requirements

- Python 3.8+
- pip

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/Atreus2004/Capstone.git
cd Capstone
