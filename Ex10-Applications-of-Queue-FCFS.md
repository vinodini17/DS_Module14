# Ex 2(E) Applications of Queue – FCFS
## DATE: 19/03/2025
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1.	Start with process, burst time, and waiting time arrays.
2.	Loopthrough each process from i= 0 to n-1.
3.	Compute tat[i] = burst_time[i] + wait_time[i].
4.	End the algorithm.
   

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: KAVIYA D
RegisterNumber:  212223040089
*/

int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[])
 {
// calculating turnaround time byadding
// burst_time[i] + wait_time[i] int i;
for ( i = 0; i < n ; i++)
tat[i] = burst_time[i] + wait_time[i]; return 0;
}

```

## Output:

![image](https://github.com/user-attachments/assets/415ad69b-2c73-422b-a90b-4f1bfd2a84d3)


## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
