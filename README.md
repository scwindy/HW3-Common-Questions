# HW3 Common Questions
## Summary
All the questions are covered by lecture slides.
## Q1
Each sub question has only one correct choice.
### Q1.4 What is the meaning of this question?
For Q1.4 (D) "Bounded waiting implies no deadlock", it basically means "if there is bounded waiting, then there will be no deadlock". "IMPLY" has the similar meaning in Discrete mathematics. You can check each statement is true or not, and then pick the correct choice. If you think this question has no correct choice, you can also write down the reason
### Q1.7 Does lock and unlock mean literally calling pthread_mutex_lock(&mutex) and pthread_mutex_unlock(&mutex) in the code segment?
Yes, I think you can think so.

## Q2
### Q2.1 What do you mean for “problem”? 
The meaning is “the negative consequences”.
### Q2.4 We are required to illustrate how it prevents deadlock. Do I have to proof it, or just explain how it work?
I think you only need to explain it in a little more details. We are not expecting a formal proof.

## Q3
### Q3.1 Will the order of instructions in the same process change as well?
The answer is NO. In other words, A1 must appear before A2, and B1 must appear before B2.


## Q4
### Q4.2/Q4.3 Does it suffice to just explain the reasons by saying after we pretend to grant the request, i.e. modify the available vector and allocation matrix accordingly, we then run the banker’s algorithm and it returns unsafe?
For both sub questions, here are my suggestions. If your answer is NO, you can write down which process cannot be fulfilled. If your answer is YES, you can write down an order in which the processes may complete (ie just like Q4.1).

