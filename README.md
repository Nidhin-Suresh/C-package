# SJF-implementation

SJF stands for shortest job first, this algorithm considerably reduces the CPU waiting time
This C code implements Non-preemptive SJF assuming that all the processes arrive at the same time
This code uses array data structure to implement the algorithm.
Individual arrays keep track of the processes and also burst, turnaround and waiting time
The limitaion of this code is that it does not work for processes arriving at different times
and because of the array implementation the number of processes are restricted, 
another drawback is that using arrays leads to memory wastage.
