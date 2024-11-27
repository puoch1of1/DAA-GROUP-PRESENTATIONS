# DAA-GROUP-PRESENTATIONS

## GROUP MEMBERS
1. OGWANG ANDREW - S23B23/050
2. OPIFUDRIRA TIMOTHY - S23B23/086
3. PUOCH MABOR MAKUEI - S23B23/055

## Project Overview
The Personal Scheduling Assistant is a Python-based application designed to help users efficiently manage and prioritize their daily tasks. The project uses object-oriented programming principles and integrates dynamic programming for task optimization, while also providing a Gantt chart visualization to present the task schedule graphically.
Objectives:
•	Manage tasks with attributes like description, deadline, priority, type, and duration.
•	Sort and display tasks based on different criteria (deadline, priority, type).
•	Optimize the task schedule to maximize priority within a limited available time.
•	Visualize the task schedule using a Gantt chart.

## Pseudocode
START
- Initialize an empty list for tasks.
LOOP:
    User can choose to:
        1. Add a task
        2. Sort tasks by deadline, priority, or type
        3. Search for a task by deadline
        4. View Gantt chart
WHEN adding a task:
    - Get task details from the user.
    - Create a task with description, deadline, priority, type, and duration.
    - Insert the task into the list (keep the list sorted by deadline).
WHEN sorting tasks:
    - Show the list sorted by deadline, priority, or type.
WHEN searching for a task:
    - Get the search deadline from the user.
    - Use binary search to find the task by deadline.
    - Show the task details or an error if not found.
WHEN showing Gantt chart:
    - Display a chart showing all tasks as bars, with the position and length based on their deadline and duration.
END


