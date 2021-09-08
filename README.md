# C++ Simulation System

#7 This c++ simuLation code do the following

//you can test this code on the schedule example at slide 15 in this file name (CS305 System Modelling and Simulation Section #2.pdf) 
//N.B: this file is in the containing folder


1- takes 2 types of input: (doesn't have to be file you can chose the input format )

1) inter-arrival times / service times

2) inter-arrival times and probability / service times and probability (generate inter-arrival / service times from random numbers)

2- calculates the values for the columns specified in the simulation table

3- calculates the following statistics:

1) average waiting time
2) probability of waiting
3) probability of server idling
4) average service time
5) average inter-arrival time (time between arrivals)
6) average waiting time (for those that do wait)
7) average time in the system
8) server utilization
9) average queue length



//N.B: This PART IS NEEDED TO BE DONE IN OUR CODE AT THE SECOND CASE IN THE SWITCH CASE

interarrival   probability   Range
0               0.23	     000---+ [230-1]--->229
1	       	0.37	     230---+ [370-1]--->599	
2		0.28	     600---+ [280-1]--->879	
3		0.12	     880---+ [120-1]--->999


Given    R.Ns: 786  903  240  874  308  237  490  128  787  364
equivalent to: 2    3    1    2    1    1    1    0    2    1


Service	       probability  Range
20		0.15	    00---+ [15-1]--->14	
25		0.25	    15---+ [25-1]--->39
30		0.35        40---+ [35-1]--->74
35		0.25	    75---+ [20-1]--->99


Given    R.Ns: 11   86   79   34   81   1   37   85   42   56
equivalent to: 20   35   35   25   35   20  25   35   30   30

