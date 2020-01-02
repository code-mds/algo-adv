# algo-adv
Algoritmi Avanzati

# Touring Machine Simulator
http://math.hws.edu/eck/js/turing-machine/TM.html


# Blind Graph Search

## DFS: Depth First Search
https://www.geeksforgeeks.org/depth-first-search-or-dfs-for-a-graph/

## BFS: Breadth First Search
https://www.geeksforgeeks.org/breadth-first-search-or-bfs-for-a-graph/

## Iterative Deeping Search
https://www.geeksforgeeks.org/iterative-deepening-searchids-iterative-deepening-depth-first-searchiddfs/

| Nome algoritmo | completezza | ottimalita' | spazio | tempo | note | 
|-|-|-|-|-|-| 
| BFS | SI | SI | 2^n | 2^n |  (esponenziale) |
| Uniform cost  | SI |	SI |	2^n |	2^n |  | 
| DFS: Depth First | NO | NO | n | 2^n | Ricerca in profondita' Frontiera mantenuta come LIFO |
| DLS: Depth Limited	| se goal prima del limite |NO | n | 2^n | mette un threashold |
| ID: Iterative Deeping | SI | SI | n | 2^(n+1) | ripeto n volte la ricerca in profondita' | 
| Bidirectional | SI | SI | 2^(n/2)	| 2^(n/2) | | 

# Informed Graph Search 

## Uniform Cost Search
https://www.geeksforgeeks.org/uniform-cost-search-dijkstra-for-large-graphs/

## Best First Search
https://www.geeksforgeeks.org/best-first-search-informed-search/

## A* Search
https://www.geeksforgeeks.org/a-search-algorithm/
