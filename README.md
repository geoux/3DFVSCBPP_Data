# 3DFVSCBPP_Data

This repository contains the data and results related to th computational experiments for the two dimensions fuzzy variable size and cost bin packing problem. There are three folders for 3 sets described as follows.

1. Set 1: There are three small crisp instances (for each cost/capacity relationship function) with items weights randomly drawn within [20, 120] and J ∈ {50, 100, 150}.
2. Set 2: The VSCBPP is studied from different perspectives. It is formed as follows:
* n ∈ {100}, m = [3, 5], W ∈ {100, 120, 150} and W ∈ {50, 75, 100, 125, 150, 175}.
* n ∈ {200}, m = [3, 5], W ∈ {100, 120, 150} and W ∈ {50, 75, 100, 125, 150, 175}.
* n ∈ {500}, m = [3, 5], W ∈ {100, 120, 150} and W ∈ {50, 75, 100, 125, 150, 175}.
* n ∈ {1000}, m = [3, 5], W ∈ {100, 120, 150} and W ∈ {50, 75, 100, 125, 150, 175}.
3. Set 3: Instances with a higher number of bin typesand items number:
* n ∈ {1000}, m = 6, w ∈ {1..100}, W ∈ {50, 75, 100, 125, 150, 175}.
* n ∈ {2000}, m = 12, w ∈ {1..100},
W ∈ {25, 50, 75, 100, 125, 150, 175, 200, 225, 250, 275, 300}

Within every folder (G1, G2 and G3) it can be found 3 more folders that contain the following:
Instances contains the excel files with the instances.
Approximate Pareto Front: the excels file corresponding to each instance with the integrated pareto front.
Solutions: the files ended with "_full" contain the integrated pareto front of the 30 executions of every algorithm. Also, it can b found the packing for each solution of each instance with each algorithm.