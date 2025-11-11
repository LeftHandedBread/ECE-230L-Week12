# Number Theory: Addition

In this lab, you’ve learned about One Hot and Binary state machines and how to build them.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Summary
In this lab I made some state machines, and it wasn't too hard. The first one was using one-hot addressing, where the one hot wire is the active state, and the other was binary, where the active state was a binary representation of hot wires.

## Lab Questions

### Compare and contrast One Hot and Binary encodings
The one hot is just one bit per state flip/flop, so when you have one state, all others are 0, and binary is where all of the states are represented in binary.
### Which method did your team find easier, and why?
One hot was easier becuase we didn't have to do K-maps or anything, it was just kind of plug and play.

### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.
It's probably pretty good for control logic, and it's probably pretty efficient for storing sequentially interesting stuff.
