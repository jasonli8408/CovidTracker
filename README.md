# path finder
#this is a project that educates users on path finding algorithms, we included the following algorithms: 
1. A* 
2. Dijkstra 
3. Bi-directional Dijkstra
4. Holistic value search (greedy). Does not give the shortest path 
5. Breadth first search (BFS) note that BFS can not go diagnal

#To use this application:
1. hold **s** on keyboard to place a starting point 
2. hold **e** on keyboard to place the ending point 
3. hold **b**, and drag the mouse across the grid to create your own obstables to challenge the path finding algorithms. Or simply select "make maze" button to randmoly generate a maze. 
4. select desired algorithms from the drop box and run the find path algorithms using the find path button.
5. one can also **remove obstables** or **remove everything** by selecting the corresponding buttons.


To demonstrate the process of the algorithms, we employed the **Observer Design Pattern** to show the exploration of process at each iteration. This is a very effective and concise way to visually demonstrate how each algorithms differ in terms of exploation process and run time. 

addition note :

    if the user desires to slow down the process of the algorithms at each iteration, simply uncomment timer delay code in the update method in the GUI class

    

