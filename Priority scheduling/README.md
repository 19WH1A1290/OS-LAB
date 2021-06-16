Aim - Write a program to Priority Scheduling

Algorithm :

1. Start the process
2. Accept the number of processes in the ready Queue
3. For each process in the ready Q, assign the process id and accept the CPU burst time
4. Sort the ready queue according to the priority number.
5. Set the waiting of the first process as ‘0’ and its burst time as its turn around time
6. For each process in the Ready Q calculate
         (a) Waiting time for process(n)= waiting time of process (n-1) + Burst time of process(n-1)
         (b) Turn around time for Process(n)= waiting time of Process(n)+ Burst time for process(n)
7. Calculate
         (a) Average waiting time = Total waiting Time / Number of process
         (b) Average Turnaround time = Total Turnaround Time / Number of process
8. Stop the process
