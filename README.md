# Fixed-Point-Vs-Floating-Point
Just type make INT=500 in terminal
# Problem Statement
In this part, you will learn how to use tools to improve your productivity. You will first document how 
performance scales with matrix size. 

To make the assignment more meaningful, we will look at the use of fixed point arithmetic in the 
context of matrix multiplication. Subsequently, you will implement Matrix Multiplication in fixed point 
to (potentially) improve the performance. 

What do you have to do:

1 Go through the mathworks link and the other link thoroughly

2 Get matrix Multiplication (on random input values) working

3 Use make and project structure as discussed

4 Vary n – the size of the matrix

5 Log the runtimes

6 Plot the graph using gnuplot

7 Implement fixed point arithmetic (basically addition and multiplication)

8 16/32 bit word

9 Q8/Q12/Q16/Q24

10 Repeat steps of the previous bullet using Fixed point

# Tasked performed

In Makefile folder directories with name as given below has been created. 
 -include
 -lib 
 -src 
 -obj 
 -bin 
1 Makefile created

2 Lib directory contains fixedptc.h file 

3 src directory contains fixedpt_print, matrix.c and print_matrix.c 

4 obj directory contains all the object files created when .c files are executed 

5 bin directory contain the executable file 

6 Implemented fixed point multiplication and floating point multiplication in c & matlab 

7 Dimension of every matrix is changing by 5 

8 Every time a random matrix is generated 

9 Random matrix is multiplied with itself and the time it takes to calculate is noted down to file 

10 Time is calculated for both floating point and fixed-point matrix multiplication 

11 Graph plotted using gnu plot in which time is y axis and log of dimension is x axis 

12 In terminal window we only have type make INT=”Value Of Maximum Dimension” and graph 
will be generated and will also get saved in Makefile directory 

13 Graph has been plotted in matlab to compare performance of C and Matlab 
# Conclusion

1 Time taken in MATLAB for Floating point matrix multiplication is less compared to 
time taken in C, Performance of MATLAB here is more. 

2 Time taken in MATLAB is more for Fixed point matrix multiplication when compared 
to C, Performance of MATLAB is less 

3 Time taken for execution of Fixed-point multiplication is more than floating matrix 
multiplication in both C and MATLAB. 

4 The difference in time of execution for MATLAB and in C is because of the algorithm 
written in MATLAB may have more time complexities and space complexities as 
compared to the one in C. 

