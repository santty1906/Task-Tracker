# Task Tracker

Task Tracker is a C-based console application designed to help small companies monitor the weekly progress of tasks across different projects. The program allows users to input task data, track their status over a 12-week period, and generate progress summaries for each project.

## Features

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

## Compilation and Execution

To compile and run the program, use a C compiler and copy the code.
