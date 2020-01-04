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
| Nearest Neighbour | https://users.cs.cf.ac.uk/C.L.Mumford/howard/NearestNeighbour.html |
| Multiple Fragment | simile a Kruskal  https://users.cs.cf.ac.uk/C.L.Mumford/howard/Multi-Fragment.html |
| Farthest Insertion | https://users.cs.cf.ac.uk/C.L.Mumford/howard/FarthestInsertion.html |
| Space filling Sierpinski | crea un frattale proporzionale alla densita' dei nodi https://en.wikipedia.org/wiki/Sierpi%C5%84ski_curve |

# Local Search
- parto da una soluzione ammissibile costruita con algo costruttivo
- calcolo soluzioni vicine tramite lo scambio di un arco
- se ho un miglioramento eseguo lo scambio 
- ripeto fino a quando non trovo soluzioni migliorative

| Nome algoritmo | note |
|-|-|
| Hill Climbing | https://www.javatpoint.com/hill-climbing-algorithm-in-ai |
| 2, 2.5, 3 Opt |  |
| Simulated Annealing |  |
