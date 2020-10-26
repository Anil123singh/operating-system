# operating-system
A set of processes are being scheduled using a preemptive, Round Robin 
scheduling algorithm. Each process is assigned a numerical priority, with a 
higher number indicating a higher relative priority. In addition to the 
process listed below, the system also has an idle task (which consumes 
no CPU resources and is identified as P_idle). This task has priority 0 and is 
scheduled whenever the system has no other available processes to run. 
The length of a time quantum is 10 units. If a process is preempted by a 
higher-priority process, the preempted process is placed at the end of the 
queue. Use following data as one of the test cases.
Thread Priority Burst Arrival
P1 40 20 0
P2 30 25 25
P3 30 25 30
P4 35 15 60
P5 5 10 100
P6 10 10 105

Write a C code to 
a. Show the scheduling order of the processes using a Gantt chart.
b. What is the turnaround time for each process?
c. What is the waiting time for each process?
d. What is the CPU utilization rate?
