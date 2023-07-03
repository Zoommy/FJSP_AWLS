# Format of solution files
A solution file contains M lines of integers, which represent the task allocation and sequencing on M machines. The i-th line represents the ordered list of operations executed on machine i. The first integer in each line represents the number of operations E processed by machine i, followed by E consecutive pairs separated by whitespace. Each pair (J, O) represents operation O of task J being processed, and the order of appearance of the pairs indicates the processing sequence on machine i.

For example, the following solution file represents the task allocation and sequencing on 2 machines:
- Machine 0 performs 3 operations: operation 1 of task 1, operation 0 of task 0, and operation 0 of task 2.
- Machine 1 performs 2 operations: operation 1 of task 0 and operation 0 of task 1.

```
3    1 1  0 0  2 0
2    0 1  1 0
```

Please note that the above example is formatted for readability, but in actual cases there may not be whitespace separation between pairs of integers.