# algo-adv
Appunti su Algoritmi 

# Touring Machine Simulator
http://math.hws.edu/eck/js/turing-machine/TM.html

# Blind Graph Search

| symbol | note | 
|-|-| 
| n | nodes |
| b | max branch factor |
| m | max depth |
| d | depth to solution |
| n^2 | max edges |
| n! | max path |

| Nome algoritmo | completezza | ottimalita' | spazio | tempo | note |
|-|-|-|-|-|-|
| DFS: Depth First | NO | NO | n (bm) | 2^n (b^m) | Ricerca in profondita', Frontiera mantenuta come LIFO  https://www.geeksforgeeks.org/depth-first-search-or-dfs-for-a-graph |
| DLS: Depth Limited | SI* |NO | n | 2^n | completo se goal prima del limite |
| IDS: Iterative Deeping | SI | SI | n | 2^(n+1) | ripeto n volte DLS aumentando il limite di 1  https://www.geeksforgeeks.org/iterative-deepening-searchids-iterative-deepening-depth-first-searchiddfs | 
| BFS: Breadth First | SI | SI | 2^n (b^d) | 2^n (b^d) | ricerca in ampiezza  https://www.geeksforgeeks.org/breadth-first-search-or-bfs-for-a-graph |
| Uniform cost  | SI |	SI | 2^n |	2^n | esponenziale https://www.geeksforgeeks.org/uniform-cost-search-dijkstra-for-large-graphs | 
| Bidirectional | SI | SI | 2^(n/2)	| 2^(n/2) | | 

# Informed Graph Search 

| Nome algoritmo | completezza | ottimalita' | spazio | tempo | note |
|-|-|-|-|-|-|
| Best First | NO | NO | 2^n (b^m) | 2^n (b^m) |  https://www.geeksforgeeks.org/best-first-search-informed-search |
| A* Search | SI* | SI* | 2^n (b^d) | 2^n (b^d) | Ottimalita' se euristica Ammissibile e Consistente https://www.geeksforgeeks.org/a-search-algorithm/ |

https://www.javatpoint.com/ai-informed-search-algorithms

# Algoritmi costruttivi
| Nome algoritmo | note |
|-|-|
| Nearest Neighbour |  |
| Multiple Fragment |  |
| Nearest Addition |  |
| Space filling Sierpinski |  |

# Local Search
| Nome algoritmo | note |
|-|-|
| Hill Climbing | https://www.javatpoint.com/hill-climbing-algorithm-in-ai |
| Simulated Annealing |  |
