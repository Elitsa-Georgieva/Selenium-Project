# Selenium-Project
"Task Board" is a simple information system for managing tasks in a task board. Each task consists of title + description. Tasks are organized in boards, which are displayed as columns (sections): Open, In Progress, Done. Users can view the task board with the tasks, search for tasks by keyword, view task details, create new tasks and edit existing tasks (and move existing tasks from one board to another).

Selenium-based automated UI tests for the "Task Board" app:

•	Navigate to “Task Board” and assert that the first task from board "Done" has title "Project skeleton".
•	Search tasks by keyword "home" and assert that the first result has title "Home page".
•	Search tasks by keyword "missing{randnum}" and assert that no such task is found.
•	Try to create a new task, without title, and assert an error is returned.
•	Create a new task, holding valid data (name and description), and assert that the new task is added and listed last in the task board.

