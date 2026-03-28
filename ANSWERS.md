# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**

[A process is basically a program running independently, and it has its own memory and resources that it doesn’t share with others. On the other hand, a thread is a smaller unit inside a process that shares the same memory and resources with other threads. Because of that, communication between threads is much faster and easier compared to processes, which need more complex methods to communicate.

Also, threads are lighter in terms of creation and management, so they don’t take as much time or resources as processes. In this assignment, we used threads because we needed multiple tasks to run at the same time while sharing the same data. If we used processes instead, it would consume more memory and make communication slower, which would reduce the efficiency of the simulation.]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

[A process is basically a program running independently, and it has its own memory and resources that it doesn’t share with others. On the other hand, a thread is a smaller unit inside a process that shares the same memory and resources with other threads. Because of that, communication between threads is much faster and easier compared to processes, which need more complex methods to communicate.

Also, threads are lighter in terms of creation and management, so they don’t take as much time or resources as processes. In this assignment, we used threads because we needed multiple tasks to run at the same time while sharing the same data. If we used processes instead, it would consume more memory and make communication slower, which would reduce the efficiency of the simulation.]

Example from my output:
```
[
  ? P1 executing quantum [4000ms] 
  ? Quantum progress: [???????????????] 100%
  ? P1 completed quantum 4000ms ? Overall progress: [????????????????????] 44%
     Remaining time: 4919ms
  ? P1 yields CPU for context switch

  ? P1 (Priority: 3) added to ready queue ? Burst time: 8919ms
?? Ready Queue ?????????????????????????????????????????????????????????????????
? [P3 ? P4 ? P5 ? P6 ? P7 ? P8 ? P9 ? P10 ? P11 ? P12 ? P1]]
```

**Explanation of example:**
[Explain what's happening in the output snippet you pasted]
For example, in my program output, I had a process that started running but didn’t finish within the given time slice, so it was re-queued at the end. Then another process was executed, and after that, the original process came back and resumed execution. This shows how Round-Robin ensures fairness by giving each process equal CPU time instead of letting one process run for too long.
---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

[Write your answer here. For each state, explain when P1 enters that state during the simulation. Use your understanding of the code to trace through the lifecycle.]

1. **New**: [When is P1 in New state?]

2. **Runnable**: [When does P1 become Runnable?]

3. **Running**: [When is P1 Running?]

4. **Waiting**: [When/why would P1 be Waiting?]

5. **Terminated**: [When is P1 Terminated?]

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

### Example 2: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

---

## Summary

**Key concepts I understood through these questions:**
1. 
2. 
3. 

**Concepts I need to study more:**
1. 
2. 
