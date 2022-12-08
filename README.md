This is a To-Do List App, which you can create a login and access your tasks.

Once logged, you can keep up with your tasks: create a new task by clicking on the "New Task" button (if you already have tasks, click on the "plus" button to create a new one), and then provide a title and description to your task; to update or set to "complete", click on the name of the task, and you can change the name or description, and the it to complete. 
To delete a task, simply press the "X" button on the side of the name of the task, and then procced to confirm it. 

When you're done, you can logout of your account, to keep your tasks private.

Requirements:
Python 3.11 - https://www.python.org/downloads/
pip - https://pip.pypa.io/en/stable/getting-started/


How to run this app (Linux/Windows)
Create a virtual environment by following this steps:
- Open your terminal and type "$ python -m venv myvenv" ("myvenv" is the name of your virtual environment)
- Start you virtual environment by running "myvenv\Scripts\activate" (you know that worked when your console is prefixed with (myvenv))
- Clone this project: https://github.com/marymnis/todo-list
When the download ends, run this commands at your terminal:
1 - cd todo-list-main
2 - pip install -r requirements.txt
3 - python -m manage runserver 
4 - using the default port 8000, open the app on your browser
