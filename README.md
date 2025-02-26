✅ Streamlit Task Manager

A simple task management web app built with Streamlit. It lets you add, complete, and delete tasks, while keeping everything organized into completed and incomplete sections.

📂 Project Structure

├── task_manager.py       # Main Streamlit app file  
└── README.md             # Project documentation (this file)  

🛠️ Features
	•	Add Tasks: Add new tasks through an input field.
	•	Mark as Complete: Use checkboxes to mark tasks as done.
	•	View Completed Tasks: Separate section for tasks that are done.
	•	View Incomplete Tasks: Section for pending tasks.
	•	Delete Tasks: Remove tasks with a single click.
	•	Session State Persistence: Tasks stay in memory while the app is running.

⚙️ Installation & Setup
	1.	Clone the repository:

git clone https://github.com/your-repo/task-manager.git  
cd task-manager

	2.	Create a virtual environment (optional but recommended):

python -m venv venv  
source venv/bin/activate     # On Windows: venv\Scripts\activate

	3.	Install dependencies:

pip install streamlit

	4.	Run the Streamlit app:

streamlit run task_manager.py

🖥️ App Navigation
	•	Add Task: Add new tasks and view all tasks in one place.
	•	Completed Tasks: View and manage tasks that are marked as complete.
	•	Incompleted Tasks: Track and manage tasks that are still pending.

🚀 Example Workflow
	1.	Add a Task: Enter “Buy groceries” and click Add Task.
	2.	Mark as Complete: Tick the checkbox for “Buy groceries”.
	3.	View Completed Tasks: See “Buy groceries” under the Completed Tasks section.
	4.	Delete a Task: Click Delete to remove a task permanently.

📘 Future Improvements
	•	Database Integration: Save tasks to a database instead of relying on session state.
	•	Due Dates & Priorities: Add deadlines and priority levels to tasks.
	•	Task Categories: Group tasks into categories or projects.
	•	Dark Mode Support: Add a dark mode for better UI customization.

