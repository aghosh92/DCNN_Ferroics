# DCNN_Ferroics
Deep learning polarization data in ferroelectrics from STEM images

The goal of this study is to show how polarization of bismuth ferrite (BFO) doped with five different Samarium (Sm) concentrations (0%, 7%, 10%, 13% and 20%) can be predicted using deep convolution neural networks (DCNNs) with and without atom finding.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/aghosh92/DCNN_Ferroics/blob/main/DCNN_ferroics_NC_train_test_visualize.ipynb)


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/aghosh92/DCNN_Ferroics/blob/main/DCNN_ferroics_C_train_test_visualize.ipynb)


In particular the notebooks demonstrate:

(1) how a 'sliding window' approach can be utilized to generate subimages that are not centered (NC) around the atoms,

(2) how to generate subimages that are centered (C) around the atoms,

(3) how DCNNs are trained on one of the images/subimages correponding to one Sm concentration and can be applied to the other compositions,

(4) how to construct feature maps, visualize convolution layers to get insights into DCNN operations.


STEM dataset utilized in this study is available via the following link:
DOI 10.5281/zenodo.4555978
