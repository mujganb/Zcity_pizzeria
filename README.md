# Zcity_pizzeria

A problem related to minimum spanning tree. Kruskal algorithm is selected as a suitable approach to this problem which uses greedy approach to find minimum spanning tree.

#### Table of Contents

1. [Problem Overview](#Problem-overview)
2. [Project Content](#project-content)
3. [Technologies](#Technologies)

## Problem Overview
After a long deferment, the mayor of Z-city has allowed pizzerias to be opened in town. Pizzerias used to be unlawful because of health reasons (according to the mayor). The city is big, and suddenly there are pizzerias everywhere. We can imagine the city like a matrix with NxN squares, where every square represents one block of the city. Every pizzeria only delivers pizza to the nearby blocks. Specifically, every pizzeria delivers pizza to every block that is at most K blocks away from the pizzeria's block. Distance is determined by the minimum number of blocks that the delivery guy must take if he is going East/West or North/South (moving diagonally is forbidden in Z-city). For example, let's say that N=5 and a pizzeria is located at the block (3, 3). It can deliver to a 2 block distance at most. The following map shows where the given pizzeria delivers pizzas.  
  
00X00  
0XXX0  
XXXXX  
0XXX0  
00X00  
  
Mr. Little Z loves pizza, so he wants to move to the block where he can have the greatest selection of pizzas (the block that has the maximum number of pizzerias delivering to it). Help Mr. Little Z building an API to find that maximum. In other words, if he moves to the block with the greatest selection of pizzas, how many pizzerias will be able to deliver to his block?  
  
INPUT:  
The first line of the standard input contains the two numbers N and M, and both numbers are on the interval [1, 1000]. The number N represents the dimension of the city in blocks (the city has NxN blocks). M is the number of pizzerias in the city. The following M lines contain information about each pizzeria, given by the three numbers X, Y, K. The numbers X and Y represent the block where the pizzeria is located, (1 <= X, Y <= N) and the number K represents the maximum distance that the given pizzeria's delivery guy will travel to deliver pizza (1 <= K <= 1000).  
  
OUTPUT:  
Write one number to the standard output that represents the number of pizzerias that deliver pizzas to the block with the greatest selection of pizzas.

## Project Content

- zcity_pizzeria.ipynb  
A file containing API for the solution of the problem described. Returns the number of pizzerias that delivers in the best spot of the city.  

- test.txt  
A file to test the API.  

- report.txt  
A file on how I approached this problem briefly.  

## Technologies

Project is created with Python 3

