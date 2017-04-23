# Team Members:
1) Aakarshan Gupta 
2) Himanshu Tolani 
3) Jatin Garg 
4) Saumya Goyal 
5) Skand Vishwanath Peri 
----------------------------------------------------------------------------------------------------------------------------------

# Description of Program:
This program takes in basic C text file as an input (input to be given in input.txt) and simulates that C program and results the output.


----------------------------------------------------------------------------------------------------------------------------------

# Description of the Grammar: [with print and read commands]

P -> S; | S;P 
S -> A | W | R | O
A -> V1 = E
W -> while(E){P}
V1 -> V | Vi
V -> {a-z}+ [except while]
Vi -> V[E]

E -> E < E1 | E == E1 | E1
E1 -> E1 + E2 | E1 - E2 | E2
E2 -> E2 * E3 | E2 / E3 | E3
E3 -> (E) | V1 | C
C -> {0-9}+ . {0-9}k | {0-9}+

R -> read V1
O -> print V1 | print C

Here 0 <= j <= B is the precision limit of the decimal point
----------------------------------------------------------------------------------------------------------------------------------


# NOTE : 
The name of the file is input.txt.
The precision of the decimal point is taken (by default) to be 8.

----------------------------------------------------------------------------------------------------------------------------------

# Instructions to run and compile the code:

Compile:
gcc simulator.c

Run
./a.out

The output can be viewed in output.txt file that would be created.
----------------------------------------------------------------------------------------------------------------------------------

