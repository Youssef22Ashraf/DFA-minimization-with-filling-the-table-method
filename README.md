# Deterministic Finite Automata (DFA) Minimization with filling-the-table-method

## Description 
This Python software accepts a description of a deterministic finite automaton (DFA) and returns a minimized version of that DFA. The script initially prompts the user to provide information on the DFA, such as its states, alphabet, initial and final states, and transition functions. It then creates a DFA graph using the PyGraphviz module, visualizes it, and utilizes a table-filling method for minimization, merging comparable states. Finally, it outputs the minimized DFA, transition table, and visualizations, following the equivalence theorem.

## Input Format 
- The user is prompted to input:
  - Alphabet
  - Initial state
  - Final state(s)
  - State values
  - Transition functions

## Output Format 
- The script outputs:
  - Initial state of the minimized DFA
  - Final state(s) of the minimized DFA
  - Transition table of the minimized DFA
  - Visualization of the minimized DFA graph

## Inside Mechanism 
Contributed to developing the DFA minimization project, a Python tool that optimizes Deterministic Finite Automata (DFA) by reducing states while preserving language recognition. Using a table-filling method, the script systematically analyzes state transitions, identifying and merging equivalent state pairings to create a minimized DFA. It leverages PyGraphviz for graph visualization and the OS library for system commands, providing essential DFA information to enhance understanding of automata theory and algorithmic optimization.

## Tools and Libraries
The script is written in Python, a high-level programming language known for its simplicity and readability. It utilizes several tools and libraries:
- PyGraphviz: A Python interface to the Graphviz graph layout and visualization package, enabling the creation, manipulation, and visualization of graphs.
- Graphviz: An open-source graph visualization software providing tools for generating graph layouts and rendering them into various formats.
- Operating System Commands: The script uses operating system commands via the OS module to execute commands like opening an image file for visualization.
