Matrix Factorisation for Scalable Energy Breakdown
-------------------

This repository contains the code for our [AAAI 2017 paper](https://nipunbatra.github.io/papers/batra_aaai2017.pdf) entitled: Matrix Factorisation for Scalable Energy Breakdown

Please use the following bib for citing our work

```
@inproceedings{batra2017matrix,
  title={Matrix Factorisation for Scalable Energy Breakdown},
  author={Batra, Nipun and Wang, Hongning and Singh, Amarjeet and Whitehouse, Kamin},
  booktitle={AAAI 2017},
  year={2017}
}
```




Notebooks used to generate the plots/tables in the paper
----------------------------

1. [Figure 1](https://github.com/nipunbatra/mf-energybreakdown/blob/master/notebooks/dataset-plots.ipynb)
2. [Table 2](https://github.com/nipunbatra/mf-energybreakdown/blob/master/notebooks/all_feature_homes-fraction.ipynb)
3. [Table 3](https://github.com/nipunbatra/mf-energybreakdown/blob/master/notebooks/final-all-homes.ipynb)
4. [Figure 2, Figure 3](https://github.com/nipunbatra/mf-energybreakdown/blob/master/notebooks/all_feature_homes-fraction-big-matrix.ipynb)

Other important code to look at
-------------------------

1. [Main matrix factorisation CVXPY code](https://github.com/nipunbatra/mf-energybreakdown/blob/master/code/matrix_factorisation.py)
2. [KNN baseline](https://github.com/nipunbatra/mf-energybreakdown/blob/master/code/knn_subset.py)
3. [Code to run MF on HPC Slurm cluster](https://github.com/nipunbatra/mf-energybreakdown/blob/master/code/harness_cluster.py)
4. 




**NB** This work was built upon as an improvement to our KDD 16 work called- Gemello: Creating a Detailed Energy Breakdown from just the Monthly Electricity Bill [Paper pdf](https://www.iiitd.edu.in/~nipunb/papers/gemello.pdf) , [Youtube video](https://www.youtube.com/watch?v=pzgqd9OhvDA), [Poster](https://www.iiitd.edu.in/~nipunb/slides/kdd_poster_final.pdf)