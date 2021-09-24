# Graph Theory

## About
This repository concerns about the graph theory discipline algorithms required for our second avaliation.

## Group
* Rick Martim Lino dos Santos
* Rafael Emílio Lima Alves

## Structure
The main structure of this repository is: 
* The directory for each algorith with:
  * The .cpp code for each of the chosen algorithms.
  * The input file for each algorithm.
  * The makefile.

## Makefile
The Makefile has only two main commands:
* make: When you are in one of the algorithm directories the "make" command in the prompt will generate the binary file of the application alongside with the .o file.
* make clean: When you declare the "make clean" command in the prompt you will delete all the files generated with the make command, reverting the directory to have only its original files.

## Algorithms

### Dijkistra Algorithm

#### Input Structure
The input for our aproach in dijkstra algorithm it's a first line for the number of verticles and edges followed by a number of lines, corresponding to the number of edges, wich each one is a line for the graph's adjacency list. At the end of those lines we receive in a line two int variables reguading to the start vertex and the destiny vertex.
```
7 9
5 3 9
2 0 24
0 3 3
1 2 4
0 1 5
1 5 20
5 2 1
5 4 6
2 6 18
1 3
```

#### Running
For running Dijkistra Algorithm you locate its directory and execute the make for generate its bin. With the bin file `dijkstra` generated, execute the follow command in the prompt:`./dijkstra`, than type your input according to above configuration.

#### Running with file input:
For running Dijkistra Algorithm with our file example input, follow the steps above but in the call of the bin file, type `./dijkstra < your input file name`, so for our input example we have the following `./dijkstra < dijkstraInput`

<hr>

### Ford Fulkerson Algorithm
#### Input Structure
The input for our aproach in ford fulkerson algorithm it's a first line for the number of verticles and edges followed by a number of lines, corresponding to the number of edges, wich each one is a line for the graph's adjacency list. At the end of those lines we receive in a line two int variables reguading to the start vertex and the destiny vertex.
```
5 6
0 2 5
0 3 3
3 1 5
2 1 2
1 4 7
2 4 2
0 4
```

#### Running
For running Ford Fulkeron Algorithm you locate its directory and execute the make for generate its bin. With the bin file `fordFulkerson` generated, execute the follow command in the prompt:`./fordFulkerson`, than type your input according to above configuration.

#### Running with file input:
For running Ford Fulkerson Algorithm with our file example input, follow the steps above but in the call of the bin file, type `./fordFulkerson < your input file name`, so for our input example we have the following command: `./fordFulkerson < fordFulkersonInput`

<hr>

### Kruskal Algorithm
#### Input Structure
The input for our aproach in Kruskal algorithm it's a first line for the number of verticles and edges followed by a number of lines, corresponding to the number of edges, wich each one is a line for the graph's adjacency list. 
```
8 16
0 2 4
0 3 6
0 4 2
1 5 3
1 6 3
2 0 4
3 0 6
3 5 1
4 0 2
4 6 6
4 7 8
5 1 3
5 3 1
6 1 3
6 4 6
7 4 8
```

#### Running
For running Kruskal Algorithm you locate its directory and execute the make for generate its bin. With the bin file `kruskal` generated, execute the follow command in the prompt:`./kruskal`, than type your input according to above configuration.

#### Running with file input:
For running Kruskal Algorithm with our file example input, follow the steps above but in the call of the bin file, type `./kruskal < your input file name`, so for our input example we have the following command: `./kruskal < kruskalInput`

<hr>

### Prim Algorithm
#### Input Structure
The input for our aproach in Prim algorithm it's a first line for the number of verticles and edges followed by a number of lines, corresponding to the number of edges, wich each one is a line for the graph's adjacency list. 
```
9 13
0 1 4
0 7 8
1 2 8
1 7 11
2 3 7
2 8 12
2 5 4
3 4 9
3 5 14
4 5 2
5 6 10
6 7 9
7 8 6
```

#### Running
For running Prim Algorithm you locate its directory and execute the make for generate its bin. With the bin file `prim` generated, execute the follow command in the prompt:`./prim`, than type your input according to above configuration.

#### Running with file input:
For running Kruskal Algorithm with our file example input, follow the steps above but in the call of the bin file, type `./prim < your input file name`, so for our input example we have the following command: `./prim < primInput`

