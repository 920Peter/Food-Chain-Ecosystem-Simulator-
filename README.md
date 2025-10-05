# Food-Chain-Ecosystem-Simulator- 🌿🐇🦊🕸
C program that simulates predator–prey relationships in an ecosystem by classifying organisms into trophic levels using dynamic memory, file I/O, and structured data.

### Overview
The **Food Web Simulation** is a C program that models relationships between organisms in an ecosystem. It classifies each species as a **producer**, **consumer**, **omnivore**, or **apex predator**, depending on its interactions with others in the food web.  
The project emphasizes algorithmic problem-solving, dynamic memory management, and structured data representation.

### Features
- Builds and stores predator–prey relationships dynamically  
- Classifies organisms into trophic categories  
- Allows adding, removing, and printing organisms interactively  
- Supports multiple program modes (`basic`, `debug`, `quiet`)  
- Demonstrates robust error handling and modular program design  

### Skills Demonstrated
- Dynamic memory management (`malloc`, `realloc`, `free`)  
- Data structure design using arrays and structs  
- Command-line argument handling  
- Algorithm design and classification logic  
- Debugging with Valgrind and GDB  

### How to Compile
```bash
gcc -g -Wall -std=c11 mainFINAL.c -o foodweb
