# Fitnees Tracker Management System

## Overview
The **Exercise Management System** is a Python-based program that allows users to log, view, save, and load their workouts. This simple command-line tool helps users keep track of their fitness activities.

## Features
- **Enter a Workout**: Log the date, type of workout, and duration.
- **View Workouts**: Display all recorded workouts.
- **Save Workouts to a File**: Save the workout history to a file.
- **Load Workouts from a File**: Load previously saved workouts.
- **User-Friendly Menu**: A simple interface for easy navigation.

## Installation
To run this program, you need to have **Python 3** installed on your system.

### Steps to Run the Program:
1. Clone or download the repository.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script is located.
4. Run the script using the following command:
   ```bash
   python exercise_management.py
   ```

## Usage
After running the script, you will see a menu with the following options:
```
Exercise Management
1. Enter workout
2. View workouts
3. Save workouts
4. Load workouts
5. Exit
```

### Example Usage
1. **Entering a Workout:**
   - The program will prompt you for the **date**, **workout type**, and **duration**.
   - Example input:
     ```
     Enter workout date (YYYY-MM-DD): 2025-02-20
     Enter type of workout: Running
     Enter workout duration (in minutes): 30
     Workout added successfully.
     ```

2. **Viewing Workouts:**
   - The program will list all recorded workouts.
   - Example output:
     ```
     2025-02-20 | Running | 30 minutes
     ```

3. **Saving Workouts to a File:**
   - Enter a filename to save the workouts.
   - Example:
     ```
     Enter filename to save workouts: my_workouts.txt
     Workouts saved to my_workouts.txt.
     ```

4. **Loading Workouts from a File:**
   - Enter the filename containing saved workouts.
   - If the file exists, workouts will be loaded.
   - Example:
     ```
     Enter filename to load workouts: my_workouts.txt
     Workouts loaded from my_workouts.txt.
     ```

## Code Structure
The program is implemented using a class-based approach:
- **`ExerciseManagement` Class**
  - `__init__()` - Initializes an empty list to store workouts.
  - `enter_workout()` - Takes user input and stores a workout entry.
  - `view_workouts()` - Displays all stored workouts.
  - `save_workouts()` - Saves workouts to a file.
  - `load_workouts()` - Loads workouts from a file.
  - `menu()` - Provides a user-friendly menu for interaction.

## Error Handling
- Handles **File Not Found** errors when loading workouts.
- Ensures the user provides valid inputs where necessary.

## Future Improvements
- Add **data validation** for date format and numeric inputs.
- Save workouts in **CSV format** for better structuring.
- Implement a **GUI version** using Tkinter or PyQt.

## License
This project is licensed under the **MIT License**.

## Author
**Harsh Purushottam Kulkarni**

