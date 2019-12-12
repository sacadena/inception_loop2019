# Inception Loop Code
In this repository, you'll find code used for the [Walker et al. 2019 *Nature Neuro*](https://www.nature.com/articles/s41593-019-0517-x) to execute inception loops. In particular, you will find code necessary to perform neural network training and hyperparameter selection (`staticnet_experiments`) and Most Exciting Input (MEI) generation (`staticnet_analyses`). This repository makes heavy use of [DataJoint](https://datajoint.io), with explicit dependencies on schemas defined in https://github.com/cajal/pipeline and https://github.com/cajal/neuro_data. Hence running the closed loop code as given requires setting up the pipeline in its entirety. However, if you are just interested in the model details and in the MEI generation code, refer to `staticnet` and `staticnet_experiments` for how models are put together, and for `staticnet_analyses` package (in particular `multi_mei.py` and `utils.py`) for how MEIs are generated. 