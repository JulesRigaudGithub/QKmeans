# QKmeans
An updated version for updated Qiskit :
```
qiskit==0.45.1
qiskit-aer==0.13.2
qiskit-ibm-provider==0.8.0
qiskit-ibm-runtime==0.17.0
qiskit-terra==0.45.1
```




From the original repo of Alessandro Poggiali : https://github.com/AlessandroPoggiali/QKmeans
### QKmeans
Quantum version of the k-means clustering algorithm. Three versions of the algorithm are implemented:

1) q-k-means-1: it makes parallel the distance computation between a pair of dataset record
2) q-k-means-2: it makes parallel the cluster assignment to a given record
3) q-k-means-3: it makes parallel the entire step of cluster assignment to every record

reference paper: https://arxiv.org/pdf/2212.06691
