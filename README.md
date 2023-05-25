# MapReduce

## How to compile 
```rustc -o main main.rs```

## Description 
This is a program that implements the map reduce algorithm created by Google. 
Map reduce aims to take data running in parallel and compute it simultaneously.
By Creating the re-creating the algorithm in rust we're able to ensure the memory saftey of the program due to it being enforced at the compiler level.
Additionally, re-creating the algorithm provides great practice with handling multiple threads by ensuring there's no data race conditions.
