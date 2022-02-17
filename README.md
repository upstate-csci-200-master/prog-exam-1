# lab-test-1
A climate research scientist has employed your services. She needs you to develop a program to help her discover trends in temperature data. She wants to know what the average temperature is over a period of 1 week. But she wants 2 different averages. One for the even numbered days (2, 4, 6) and one for the odd numbered days (1, 3, 5, 7). 


Write a Java program named TempAverages that reads in 7 temperatures (floating point format) and computes these 2 averages. Output the results as 2 double precision floating point numbers separated by a single space. She wants the even day average to appear first. FOR AN A: print precisely 2 digits to the right of the decimal. For example: 98.00 or 45.40 or 0.00 etc (google to find out how to do this). 

NOTE: this program can be solved without any IF statements. Think about the order of the temps. First temp is for an odd number day, second temp is for an even number day, etc. 

Math review: the average of a group of temps is found by adding up the temps and then dividing the result of the addition by the number of temps added.

Sample Input
```
54.3 76.5 84.3 35.9 44.2 88.0 65.5
```
Sample Output
```
66.8 62.075
