# DFS and BFS
A simple example of Depth-First Search
From this binary tree implemented in python3
<img width="497" alt="Screen Shot 2021-09-22 at 12 35 41" src="https://user-images.githubusercontent.com/45419531/134284106-49e23f1f-ecf2-4e3c-95b5-00bd0acfd79b.png">

# DFS Explanation

Lines 2-9: The illustrated graph is represented using an adjacency list - an easy way to do it in Python is to use a dictionary data structure. Each vertex has a list of its adjacent nodes stored.

Line 11: visited is a set that is used to keep track of visited nodes.

Line 21: The dfs function is called and is passed the visited set, the graph in the form of a dictionary, and A, which is the starting node.

Lines 13-18: dfs follows the algorithm described above:
It first checks if the current node is unvisited - if yes, it is appended in the visited set.
Then for each neighbor of the current node, the dfs function is invoked again.
The base case is invoked when all the nodes are visited.
The function then returns.


# BFS Explanation
Lines 3-10: The illustrated graph is represented using an adjacency list. An easy way to do this in Python is to use a dictionary data structure, where each vertex has a stored list of its adjacent nodes.

Line 12: visited is a list that is used to keep track of visited nodes.

Line 13: queue is a list that is used to keep track of nodes currently in the queue.

Line 29: The arguments of the bfs function are the visited list, the graph in the form of a dictionary, and the starting node A.

Lines 15-26: bfs follows the algorithm described above:

It checks and appends the starting node to the visited list and the queue.
Then, while the queue contains elements, it keeps taking out nodes from the queue, appends the neighbors of that node to the queue if they are unvisited, and marks them as visited.

This continues until the queue is empty.

Source: educative.io
