# The Single Commodity Split Pickup and Split Delivery Vehicle Routing Problem (SPDVRP)
# Abstract
We present a new exact algorithm to solve a challenging vehicle routing problem with split pickups and deliv-
eries, named as the Single Commodity Split Pickup and Split Delivery Vehicle Routing Problem (SPDVRP).
In the SPDVRP, any amount of a product collected from a pickup customer can be supplied to any delivery
customers, and the demand of each customer can be collected or delivered multiple times by the same or
different vehicles. The vehicle 
eet is homogeneous with limited capacity and maximum route duration. This
problem arises regularly in inventory and routing rebalancing applications, such as in bike-sharing systems,
where bikes must be rebalanced over time such that the appropriate number of bikes and open docks are
available to users. The solution of the SPDVRP requires determining the number of visits to each customer,
the relevant portions of the demands to be collected from or delivered to the customers, and the routing of
the vehicles. These three decisions are intertwined, contributing to the hardness of the problem.
Our new exact algorithm for the SPDVRP is a branch-price-and-cut algorithm based on a pattern-based
mathematical formulation. The algorithm relies on a novel label-setting algorithm used to solve the pricing
problem associated with the pattern-based formulation, where the label components embed reduced cost
functions, unlike those classical components that embed delivered or collected quantities, thus signifficantly
reducing the dimension of the corresponding state space. Extensive computational results on different classes
of benchmark instances illustrate that the newly proposed exact algorithm solves several open SPDVRP
instances and signifficantly improves the running times of state-of-the-art algorithms.

# Key words
vehicle routing, single commodity, split pickups, split deliveries, branch-price-and-cut,
label-setting algorithm, exact algorithm

# Istances and results
We considered three classes of test instances, called SA, SB and SC, respectively. In classes SA and
SC the route duration constraints are used to impose an upper limit on the number of stops on
each route whereas class SC considers general route duration constraints. Please find from each class the file 
"README.txt", specific instances, and corresponding results.
