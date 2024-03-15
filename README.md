**Road Trip**
* We are provided with a dataset containing city names, latitude and longitude values. Additionally, information about road segments connecting cities is available in the dataset, including city names, segment lengths, speed limits, and highway names. The objective is to find the best route with minimum cost, while providing values such as the number of segments, expected hours, and number of hours of driving.

**Problem Description**
*  The initial state is determined by the starting city provided from the command line. From there, we calculate the time taken for the considered segment using distance and speed limit values provided in the dataset.
* The goal is to reach the destination city specified with the optimal cost from all given routes considered.

**Successor States:** 
* Successor states involve considering all costs from different segments. Evaluating from both the start city and destination city separately is the approach taken.

**Approach**
* The first step involved building a successor function, where all cities from start to end are considered, as well as considering the reverse direction (destination city as the starting point and starting city as the end point).
* Despite attempting to compute a more effective heuristic, an optimal path from source to destination was not achieved. Further optimization is needed while calculating costs.

**Next Steps**
* Continuing to refine the cost calculation method.
* Exploring more effective heuristic strategies.
* Implementing optimizations to achieve better route selection.
