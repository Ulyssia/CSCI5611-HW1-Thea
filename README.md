# CSCI5611-HW1-Thea

## Video    
*contains only exercise 1,2,3,5  
[https://youtu.be/K7VMdqbARUA](https://youtu.be/K7VMdqbARUA)
  
## Exercise 4：    
1. The nodes are each represented by an array item, the parent node and its visited state.  
   The edges are represented by lists of parent-child relationships.  
   Th purpose of using a visited list is to keep searching in the same level.  
   The parent list is for recording the path.  
   The right neighbor of the current node on the path is added to the fringe, so the process is in BFS order.  
   Once the goal has been reached, retrieve the parent node at each step until the start node is reached.
2. BFS has a smaller maximum fringe size.  
3. The graph is no longer a tree because some nodes have more than one parent node.  
   BFS does not find the optimal path.


## Challenge Task:        
2. Particle System: Enable color change every time the particle hits the large sphere (color switches between Blue and Green)

