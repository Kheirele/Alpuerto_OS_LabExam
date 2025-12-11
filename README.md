CS19L - OS Alpuerto Lab Exam
======================================
📌 Overview
======================================
This program implements three CPU scheduling algorithms:

- FCFS (First Come, First Served)
- SJF (Shortest Job First — Non‑Preemptive)
- Round Robin (RR)

It also includes:
Banker’s Algorithm (for deadlock avoidance)
→ Uses built‑in example matrices (no user input needed).
→ Automatically displays Need Matrix, Safe/Unsafe state, and Safe Sequence.

======================================
📌 How to Run the Program
======================================
- Make sure you have Python 3 installed.
- Save the main.py file in a folder.
- Open a terminal or command prompt inside that folder.

Run:
python main.py

======================================
📌 Input Format (Interactive)
======================================
When you run the program, it will ask for:

- Number of processes

For each process:
- Arrival Time
- Burst Time

Choose scheduling algorithm:
1 - FCFS
2 - SJF (Non-Preemptive)
3 - Round Robin


If you choose Round Robin, enter Time Quantum.

======================================
📌 Output Provided
======================================
For the chosen CPU scheduling algorithm, the program prints:

- Gantt chart (text form)
- Individual Waiting Times
- Individual Turnaround Times
- Average Waiting Time
- Average Turnaround Time

Afterward, the program automatically runs Banker's Algorithm, showing:
- Need Matrix
- Safe/Unsafe State
- Safe Sequence (if safe)

======================================
📌 Algorithms Included
======================================
✔ FCFS
Runs processes in order of arrival.

✔ SJF (Non-Preemptive)
Selects the process with the shortest burst time among the available ones.

✔ Round Robin
Uses a ready queue
Preemptive scheduling using time quantum

✔ Banker’s Algorithm
Uses provided sample matrices
Demonstrates system safety check

======================================
📌 Notes
======================================
This program handles integer inputs only.
Processes are labelled automatically as P1, P2, P3, etc.

The Gantt chart is printed in timestamp format:
P1: 0 -> 5

======================================
SAMPLE RUN
======================================
Enter number of processes: 3
Arrival time of P1: 0
Burst time of P1: 5
Arrival time of P2: 1
Burst time of P2: 3
Arrival time of P3: 2
Burst time of P3: 8

Choose algorithm:
1 - FCFS
2 - SJF (Non-Preemptive)
3 - Round Robin
Enter choice: 1

