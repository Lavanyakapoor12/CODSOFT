# CODSOFT
import json
import os

# File to store tasks
TASKS_FILE = 'tasks.json'

# Load tasks from file
def load_tasks():
    if os.path.exists(TASKS_FILE):
        with open(TASKS_FILE, 'r') as file:
            return json.load(file)
    return []

# Save tasks to file
def save_tasks(tasks):
    with open(TASKS_FILE, 'w') as file:
        json.dump(tasks, file)

# Display tasks
def display_tasks(tasks):
    if not tasks:
        print("No tasks available.")
        return
    for i, task in enumerate(tasks):
        status = '✓' if task['completed'] else '✗'
        print(f"{i + 1}. [{status}] {task['title']}")

# Add a new task
def add_task(tasks):
    title = input("Enter task title: ")
    tasks.append({'title': title, 'completed': False})
    save_tasks(tasks)
    print("Task added.")

# Update a task
def update_task(tasks):
    display_tasks(tasks)
    task_num = int(input("Enter task number to update: ")) - 1
    if 0 <= task_num < len(tasks):
        new_title = input("Enter new title: ")
        tasks[task_num]['title'] = new_title
        save_tasks(tasks)
        print("Task updated.")
    else:
        print("Invalid task number.")

# Delete a task
def delete_task(tasks):
    display_tasks(tasks)
    task_num = int(input("Enter task number to delete: ")) - 1
    if 0 <= task_num < len(tasks):
        tasks.pop(task_num)
        save_tasks(tasks)
        print("Task deleted.")
    else:
        print("Invalid task number.")

# Mark a task as complete
def complete_task(tasks):
    display_tasks(tasks)
    task_num = int(input("Enter task number to mark as complete: ")) - 1
    if 0 <= task_num < len(tasks):
        tasks[task_num]['completed'] = True
        save_tasks(tasks)
        print("Task marked as complete.")
    else:
        print("Invalid task number.")

# Main menu
def main():
    tasks = load_tasks()
    while True:
        print("\nTo-Do List Application")
        print("1. View tasks")
        print("2. Add task")
        print("3. Update task")
        print("4. Delete task")
        print("5. Mark task as complete")
        print("6. Exit")
        choice = input("Choose an option: ")

       
if choice == '1':
            display_tasks(tasks)
        elif choice == '2':
            add_task(tasks)
        elif choice == '3':
            update_task(tasks)
        elif choice == '4':
            delete_task(tasks)
        elif choice == '5':
            complete_task(tasks)
        elif choice == '6':
            break
        else:
            print("Invalid choice. Please try again.")

if __name__ == "__main__":
    main()
