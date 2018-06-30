/*
copyright by:
George Washington University
Hao Howie Huang
howie@gwu.edu
*/

This file includes four directories, top_down, bottom_up, data, translator.
1. The directory dop_down includes all the codes of top down breadth-first-search (BFS). You can run the sample graph using the command "make test". If you want to run your own graph, you need to first translate the raw edge list graph to binary csr and then modify the makefile. The input is forward csr and root vertex. The output is two files, time_detail.csv records the time of each iteration, bfs_result.txt records the result of bfs.

2. The directory bottom_up includes all the codes of bottom up breadth-first-search (BFS). Same instructions with top_down. The input is backward csr and root vertex. Output is the same with top_down.

3. The directory data includes a sample graph "epinions" from SNAP. We translate the raw edge list data to binary csr data. 

4. The translator directory includes the codes of tranlstating from a raw edge list format graph to a binary csr format graph. Follow the README file under that directory.

