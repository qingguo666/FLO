# FLO：A Novel Contrastive Mutual Information Estimator

This is the official code repository for the paper [Tight Mutual Information Estimation With Contrastive Fenchel-Legendre Optimization](https://github.com/qingguo666/FLO/blob/main/FLO.pdf).

Fenchel-Legendre Optimization (FLO) is a novel contrastive learning framework for mutual information (MI) estimation. Contrastive variational mutual information  estimators have been popularized by the successful applications of InfoNCE and its variants in machine learning. While featuring superior stability, these estimators crucially depend on costly large-batch training, and they sacrifice bound tightness for variance reduction. To overcome these limitations, FLO exploits the link between MI estimation, unnormalized statistical modeling and convex optimization. Our investigation not only yields a new unified theoretical framework encompassing popular variational MI bounds but also leads to a novel, simple, and powerful contrastive MI estimator. Theoretically, the FLO estimator is tight, and it provably converges under stochastic gradient descent; and empirically, it overcomes the above limitations of its predecessors and learns more efficiently. We demonstrate its utility through varies applications

You can clone this repository by running: 

```
git clone https://github.com/qingguo666/FLO
```


## Citation

If you reference or use our method, code or results in your work, please consider citing the [FLO paper](https://github.com/qingguo666/FLO/blob/main/FLO.pdf):

```
@article{guo2021tight,
  title={Tight Mutual Information Estimation With Contrastive Fenchel-Legendre Optimization},
  author={Guo, Qing and Chen, Junya and Wang, Dong and Yang, Yuewei and Deng, Xinwei and Carin, Lawrence and Li, Fan and Tao, Chenyang},
  year={2021}
}
```

## Contents

This repository contains the following contents. 

#### - Jupyter notebooks
Jupter notebook examples of our FLO model and various baselines (Nguyen-Wainwright-Jordan (NWJ), Donsker-Varadhan (DV), Barber-Agakov (BA), Contrastive Predivtive Coding (CPC/InfoNCE), etc.). 

#### - Experiment codes
Python codes used for our experiments. 
```
to be updated
```


#### - Results and visualization
Python codes used for the visualization of our results. 

## Prerequisites

The algorithm is built with:

* Python (version 3.7 or higher)
* PyTorch (version 1.7.1)


## Installing third-party packages
To be updated...

## Datasets
To be updated...
