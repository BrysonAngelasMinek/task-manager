🛠 Task Manager

📌 Project Overview

Task Manager is a CLI-based application designed to help users efficiently create, update, and manage tasks. Future versions may include a GUI or web interface for broader usability. The project follows best practices, emphasizing modularity, documentation, and scalability.

Primary Goal: Provide a reliable and easy-to-use CLI for task management.

Secondary Goal: Showcase development skills for a personal portfolio, highlighting clean code, testing, and a clear roadmap for potential growth.

🚀 Features

✅ Create, update, and delete tasks✅ Task statuses: Pending, In Progress, Completed✅ Due dates and filtering by status✅ SQLite database for persistent task storage✅ Error handling and input validation✅ Git version control and structured documentation✅ Roadmap available to guide future development

🔜 Future Enhancements

Task Categories (Work, Personal, Study, etc.)

Task Notifications (CLI reminders or email alerts)

REST API for external interaction (Flask/Django)

Task Prioritization (High, Medium, Low)

Web-based Interface or GUI (Flask, Django, Tkinter, PyQt)

Containerization using Docker for deployment

🏗 Installation

1️⃣ Clone the Repository

git clone https://github.com/BrysonAngelasMinek/task-manager.git cd task-manager

2️⃣ Set Up a Virtual Environment

python -m venv taskmanager-venv

On macOS/Linux:
source taskmanager-venv/bin/activate

On Windows:
taskmanager-venv\Scripts\activate

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Initialize the Database

python backend/models.py

This step creates or migrates the SQLite database locally.

5️⃣ Run the CLI Task Manager

python cli/main.py

This will launch the command-line interface for managing tasks.

📜 Usage Guide

Once the application is running, you’ll see a menu with possible actions:

Add a Task: Enter task details (title, description, due date, etc.).

List Tasks: View all existing tasks, with options to filter by status or due date.

Update a Task: Edit an existing task’s details or status.

Delete a Task: Remove a task permanently.

Exit: Quit the application.

⚙️ Tech Stack & Dependencies

Language: Python 3.x

Database: SQLite (default)

CLI Libraries: argparse or click (choose one based on preference)

Optional: tabulate, colorama/rich for enhanced CLI output

Version Control: Git (GitHub for repository hosting)

🧪 Testing

Test Framework: pytest or Python’s built-in unittest

Running Tests:

pytest

or

python -m unittest discover tests

Test Coverage (optional): Use coverage.py to measure how much of your code is covered by tests.

coverage run -m pytest coverage report -m

🛑 Note: Testing is currently at 0% because we just started the project. As we develop more features, we will expand test coverage accordingly. If you're just getting started, you can note that testing is planned, or show minimal tests and expand coverage as you implement new features.

🚧 Project Status

📌 Current Progress:

✅ Created project roadmap and initial setup plan.

✅ Set up GitHub repository.

🔄 Early Stages: Database schema design & CLI structure are next on the development list.

⚠️ Note: This project is actively evolving. Check the GitHub issues or Project Board for real-time updates on progress.

❌ No Contributions Needed

This is a personal portfolio project, and external contributions are not required. The repository is for learning and demonstration purposes.

📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

⭐ Acknowledgments

Python community resources for guidance on CLI design and SQLite integration

click / argparse for simplifying CLI command parsing

Inspiration from popular task management tools, both open-source and commercial

📌 Status: Ongoing📅 Last Updated: 2/7/2025
