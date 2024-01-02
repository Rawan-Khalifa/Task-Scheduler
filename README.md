# Task-Scheduler

## Introduction

This project is a task scheduler designed to manage and prioritize tasks efficiently.

## Key Functionalities

1. **Task Creation**: Allows users to create new tasks with a title, description, priority level, and due date.
2. **Task Prioritization**: Prioritizes tasks based on their priority value and dependencies.
3. **Task Management**: Provides functionalities to update, delete, and mark tasks as completed.

## Algorithms Used

1. **Priority Queue**: Used to manage tasks based on their priority. The task with the highest priority is served before the one with lower priority.
2. **Sorting Algorithm**: Used to sort tasks based on their due dates when they have the same priority level.

## Data Structures Used

1. **Heap**: Used as the underlying data structure for the priority queue to ensure tasks with the highest priority are served first.
2. **Array**: Used to store tasks. It allows efficient access to tasks based on their indices.

## Usage

To run the scheduler you might follow these steps:

You can choose to create a dictionary of the tasks or a more manual way of creating an instance of the Task class with all the attributes values. 

1) If you decide to create the dictionary:
- The keys will be (id, description, duration, dependencies, status, start_time, 
                 deadline, location_restricted)
- The values for the start time and deadline are either None or a specific numeric value
- The values for location_restricted is either True or False

2) Add all tasks as dictionaries in a list. 

3) Create an instance of the the TaskScheduler class taking the list of the tasks as input.

4) Call the run_task_scheduler() method of the TaskScheduler class with the start time as a parameter (in minutes).

5) This should return a list of tasks scheduled from the starting time and an overall duration to excute those tasks. 

## Thank you for using my scheduler!
