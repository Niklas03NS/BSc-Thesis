# BSc-Thesis
All code associated with the BSc thesis of Ali Al-Hadi Fadi Hussein and Niklas Sørensen on the topic of generating Pair Distance Distributions from SAXS Data using Machine Learning. 

"Data Creation_FINAL.ipynb" contains all code associated with generating datasets for individual shapes. 

"Combining Datasets.ipynb" combines and saves datasets for later training.

"Individual Shapes I(q) and I(sim) 1D CNN and MLP.ipynb" trains a CNN and an MLP on a dataset for individual shapes.

"Gridsearch_MLP_and_CNN.ipynb" is the gridsearch of the combined dataset for a CNN and an MLP. This script should be executed using a GPU due to the large computational requirements.

"Finding Isim(q) from p(r) Combined Dataset.ipynb" reconstructs I(q) from p(r) and overlays it on the ground truth I(q) with added noise.
