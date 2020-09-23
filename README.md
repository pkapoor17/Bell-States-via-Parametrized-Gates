# Bell-States-via-Parametrized-Gates

A sequence of RY, RX and CNOT gates is applied to create a bell pair of (|01>+|10>)\sqrt{2}.
Gradient Descnet is used to find the parameters.

##Results

Following is the discussion related to the outcome of the circuit on simulating with different sample sizes or the number of shots specified while executing the circuits.

###Shots = 1

Measuring the states destroyes the superposition and doing it once will give either the |01> state or the |10> state. 

![](Images/1%20shot-01.png)
![](Images/1%20shot-10.png)

###Shots = 10

Executing and measuring the circuit 10 times will give either of the states each time and their frequency of occurence can be noted which gives us the following plot(which can change on running the circuit 10 times again).

![](Images/10%20shots.png)

###Shots = 100

Increasing the number of shots increases the chances of a much more balanced plot.

![](Images/100%20shots.png)

###Shots = 1000

In the following image we can see that the chances of either of the states occuring is nearly equal.

![](Images/1000%20shots.png)
