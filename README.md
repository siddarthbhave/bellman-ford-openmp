# bellman-ford-openmp

1. run genmat.cpp: <br>
```g++ genmat.cpp``` <br>
```./a.out```

 - Input file will be created

2. run bf-omp.cpp <br>
```g++ -fopenmp -o openmp_bellman_ford bf-omp.cpp``` <br>
```./openmp_bellman_ford <input file> <number of threads>```

- you will find the output file 'output.txt'
