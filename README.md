# The quality of compression on bipartite graphs using dedensification algorithms

### Final Bachelor Project on TU/e, realized by Kacper Sawicz, supervisor dr. Nikolay Yakovets.

This repository is devoted to reproducing dedensification algorithms for graph quering. It is a part of meta-study on analyzing the combination of dedensification methods together with different graph quering algorithms. For comprehensive describrion of the project, please take a look at Bachelor_Thesis_Final.pdf . Here is a short describtion of the repo:

* All the necessary code to reproduce results as well as figures is in the [ipynb notebook on google colab](https://colab.research.google.com/drive/18p20OTDH1u23zoSwdtL3ropOZD_A2tYM?usp=sharing), which you can freely copy and use for your own purposes
* Consist of:
* * Implementation of Partition Algorithm proposed by Feder and Motwani, 1995
* * Implementation of Dedensification Algorithm proposed by Maccioni and Avadi, 2016
* * Parameters optimization based on 19 bipartite graph datasets aquired by quering YAGO2 (KDE Group, 2020) dataset
* main results:
* * The Partition Algorithm based on mathematical proof did not perform well on 17 out of 19 datasets, its limitation comes from a raw formulation
* * The Dedensification Algorithm performs well on all datasets, ideal parameter T has been found for all of them
* * By using clustering technique we can define 5 groups of datasets, which significantly differ on dedensification performance. This allows us to focus on particular datasets, on which we will perform dedensification, when we have limited computational resources

<img src="https://github.com/Kacper-Sawicz/Dedensification-of-graphs/blob/main/exmpl_ded.PNG" alt="A simple example of dedensification on a bipartite graph" width="600" height="200">



<img src="https://github.com/Kacper-Sawicz/Dedensification-of-graphs/blob/main/exmpl_ded_complicated.PNG" alt="A complex example of dedensification on a bipartite graph" width="600" height="200">



<img src="https://github.com/Kacper-Sawicz/Dedensification-of-graphs/blob/main/density%20overview.png" alt="Overview of dataset densities, with ordered nodes on x axis and amount of edges connected to it on y" width="1000" height="500">
