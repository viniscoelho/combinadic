
## Description

Combinadic class, created to be used with CUDA, generating combinations in parallel. To do so, initialize the class:
```Combination comb = new Combination(n, k)```, where ```n``` is the number of elements and ```k``` is the combination size.

To generate the **m-th** combination and retrieve it: ```comb.element(m).toArray()```
