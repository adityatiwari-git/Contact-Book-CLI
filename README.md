# 📒 Contact Book CLI Application

A simple yet effective **Command-Line Contact Book Application** developed using **Python**.  
The application allows users to **add, view, and search contacts**, with data stored persistently in a text file.

This project demonstrates core Python programming concepts and basic version control practices.

---

## 🚀 Features

- Add new contact details (Name, Phone, Email)
- View all saved contacts
- Search contacts by name
- Persistent storage using a text file
- Menu-driven and user-friendly command-line interface

---

## 🛠 Technologies Used

- **Python 3**
- File Handling (Text Files)
- Git & GitHub

---

## 📁 Project Structure

Contact-Book-CLI/
│
├── contact_book.py # Main application file
├── contacts.txt # Stores contact information
├── README.md # Project documentation
├── requirements.txt # Dependencies (none required)
└── .gitignore # Ignored files


---

## ▶ How to Run the Project

### Step 1: Clone the repository
```bash
git clone https://github.com/heyboiii19/Contact-Book-CLI.git


## Step 2: Navigate to the project directory
cd Contact-Book-CLI



## Step 3: Run the application
python contact_book.py

## 🤖 Scheduled Project Maintenance

This repository has its own GitHub Actions maintenance workflow. It is **repository-local**, so it uses GitHub's built-in `GITHUB_TOKEN` instead of a personal access token or cross-repository secret.

### What the `.github/` folder is for

- `.github/workflows/daily-maintenance.yml` — runs the scheduled maintenance workflow.
- `.github/maintenance/schedule.json` — stores this repository's assigned dates and task names.
- `.github/maintenance/run_task.py` — contains the simple, predefined task logic.

The workflow runs at **09:00 IST (03:30 UTC)** and can also be started manually.

Assigned October 2026 dates:
- 2026-10-07
- 2026-10-16

> **No meaningful change = no commit and no pull request.**

The workflow does not use Claude, OpenAI, or another external AI coding service.
