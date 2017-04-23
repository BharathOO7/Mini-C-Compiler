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

# Description of the Grammar: (with print and read commands)

P -> S; | S;P <br>
S -> A | W | R | O <br>
A -> V1 = E<br>
W -> while(E){P} <br>
V1 -> V | Vi <br>
V -> {a-z}+ [except while] <br>
Vi -> V[E] <br>
<br>
E -> E < E1 | E == E1 | E1<br>
E1 -> E1 + E2 | E1 - E2 | E2<br>
E2 -> E2 * E3 | E2 / E3 | E3<br>
E3 -> (E) | V1 | C<br>
C -> {0-9}+ . {0-9}k | {0-9}+<br>
<br>
R -> read V1<br>
O -> print V1 | print C<br>
<br>

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

