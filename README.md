# Task Tracker

Task Tracker is a simple task monitoring system for small teams or companies. It was originally developed in C as part of a university assignment, and later rewritten in Python for personal practice and learning.

## 📌 Project Versions

### ✅ C Version

The original version was built using the C programming language.

- Define multiple projects (default: 3).
- Register tasks for each project.
- Weekly task status input:
  - `0`: Pending
  - `1`: In progress
  - `2`: Completed
- Automatic marking of remaining weeks once a task is completed.
- Display total completed tasks per project.
- Identify project with the highest and lowest completion rate.
- Display percentage progress per project.

## Program Structure

The main functionality includes:

- `ingresarDatos`: Input task numbers and names for each project.
- `ingresarEstadoSemanal`: Record the weekly status of each task.
- `mostrarTareasCompletas`: Show total completed tasks by project.
- `mostrarMayorMenorPorcentaje`: Compare project completion rates.
- `mostrarPorcentajeProgreso`: Display percentage of task progress for each project.

> 📂 File: `task-tracker.c`

### 🐍 Python Version

The Python version replicates the core functionality of the C version, but with:
- Predefined task data for testing and demonstration.
- Simplified structure using lists and control flow.

> 📂 File: `task-tracker.py`
