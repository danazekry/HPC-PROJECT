# HPC-PROJECT
A comprehensive distributed computing project showcasing both traditional High-Performance Computing (HPC) methods and modern Big Data processing techniques, applied to machine learning tasks on bioinformatics datasets.
#project overview
This project explores two different distributed computing paradigms:

**Task 1:** A traditional Mini-HPC cluster utilizing MPI for distributed machine learning.
**Task 2:** A hybrid HPC-Big Data cluster built with Docker Swarm and Apache Spark.

Both methods are tested on real-world bioinformatics data, focusing on gene expression analysis for leukemia classification using the Golub dataset.
<pre> ## 🏗️ Architecture ### Task 1: Mini-HPC Cluster ``` +-------------+ +-------------+ +-------------+ | Master Node | --> | Worker 1 | --> | Worker 2 | | | | Node | | Node | +-------------+ +-------------+ +-------------+ \ | / \ | / \_____________MPI Communication_____________/ ``` ### Task 2: Docker Swarm + Spark Cluster ``` +-----------------------------------------------------+ | Docker Swarm | | | | +-------------+ +-------------+ +-------------+ | | | Spark | | Spark | | Spark | | | | Master + | | Worker 1 | | Worker 2 | | | | Jupyter | | | | | | | +-------------+ +-------------+ +-------------+ | +-----------------------------------------------------+ ``` </pre>
