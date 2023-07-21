<h1 align="center">Parallel K-Means Clustering using Open MPI</h1>

<p align="center">
  <b>Creating a parallel version of the K-Means Clustering</b>
  <br>
  <i>Making the algorithm suitable for large dataset processing</i>
</p>

<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#requirements">Requirements</a> •
  <a href="#performance">Performance</a> •
  <a href="#license">License</a> •
  <a href="#contact">Contact</a>
</p

---
---

## Introduction

This repository contains a parallel implementation of the K-Means clustering algorithm using C++ and Open MPI. K-Means is an unsupervised machine learning algorithm used for clustering data points into K clusters based on their similarity. Parallelizing the algorithm using Open MPI allows for faster processing of large datasets by distributing the workload across multiple processors or nodes.

## Requirements

- C++ compiler with C++11 support (e.g., g++ 4.8 or later)
- Open MPI library (https://www.open-mpi.org/)

## Performance

The performance of the parallel K-Means algorithm can be influenced by various factors, including the number of MPI processes, the dataset size, and the hardware configuration.

To achieve the best performance, consider adjusting the number of MPI processes based on your cluster's size and resources. Experiment with different values of K and the number of iterations to find the optimal configuration for your dataset.

Please note that the speedup gained from parallelization may vary depending on the dataset's characteristics and the number of available resources.

## License

This project is licensed under the MIT License.

## Contact

Andrea Alberti: andrea.alberti01@universitadipavia.it, andalberti99@gmail.com

Cristian Andreoli: cristian.andreoli01@universitadipavia.it

---
