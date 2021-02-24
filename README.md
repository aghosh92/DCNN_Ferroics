# DCNN_Ferroics
Deep learning polarization data in ferroelectrics from STEM images

The goal of this study is to show how polarization of bismuth ferrite (BFO) doped with five different Samarium (Sm) concentrations (0%, 7%, 10%, 13% and 20%) can be predicted using deep convolution neural networks (DCNNs) with and without atom finding.

In particular the notebooks demonstrate:

(1) how a 'sliding window' approach can be utilized to generate subimages that are not centered around the atoms,

(2) how to generate subimages that are centered around the atoms,

(2) how DCNNs are trained on one of the images/subimages correponding to one Sm concentration and can be applied to the other compositions,

(3) how to construct feature maps, visualize convolution layers to get insights into DCNN operations.
