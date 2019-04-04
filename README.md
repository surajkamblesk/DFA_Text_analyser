Introduction 


In theory of computation, a branch of theoretical computer science, a deterministic finite automaton (DFA)—also known as deterministic finite state machine—is a finite state machine that accepts/rejects finite strings of symbols and only produces a unique computation (or run) of the automation for each input string.Deterministic' refers to the uniqueness of the computation.

Problem defination
To construct a Deterministic finite automata(DFA)  that could accept any number of a’s and b’s only when the last symbol is  ‘ a ‘.The finite automata contain two states  namely q1 and q2 . 
When the input symbol is  “ a “ the finite machine changes its state from q1 to q2 state , when the input symbol is “ b” it stays in the first state only. The second state being the final state also when it encounters “a” it stays in the state  q2 only. When  the input symbol is “b” it is sent back to the state q1.
Invalid input symbols are rejected directly.

Objective
The objective of this implementation was to construct a DFA that could accept any number of a’s and b’s when the last symbol is “a”.
    • To understand and learn about the process of implementation of finite automatas .
    • To make use of Programming techniques to construct a working model of a DFA.
    • To Implement a DFA with restriction on last symbol I.e the last symbol of the input should always be a “a”.

Scope 
    • The scope of this implementation is just limited to a DFA that accepts any number of a’s and b’s .this can be further extended as a text recogniser such a one we have in C compiers I.e the Text recognisers recognises the specific text or symbol and tells whether the text / symbol belongs to that languange or not.
    • This concept can be further extended to implement a Text analyser that could not allow some specific text or symbols such as some programming languages doesnt allow some of the special charectors .
    • The possibilities are many more of this Concept of DFA implementation.

Methadology
    •  C programming Sturctures and enums.
    • Reading a string from stdin and applying the finite automata ruless on it such as to check whether the input string is acceptable or not according to the finite automata rules.
    • Based upon the  input symbol the state  of the machine is chnaged that is from state q1 to q2.

Finite automata implemented 

















Conclusion
The finite automata DFA is implemented using C programming langunage and this concept is not only limited to a string acceptor , it can be extended to many more things and application such as the text recognisers in any compilers or in a text analyser program.
