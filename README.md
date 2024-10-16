# Traffic-Prediction

Wehavemeasuredthe performance of ANN and LSTM predictorsin termsof MSE, MAE, R2, but…
What is the impact of thesemetricsfor a network operator?
How doesan operator act afterpredictingtraffic?
Do over/under-estimationof trafficprovidethe sameeffect?
Evaluate the impact of traffic over/under-estimation.

1- Calculate min and max traffic values of the dataframecreated in task 2b) and scaled ground-truth, ANN-predicted and LSTM-predicted traffic traces (test set) so as to have maximum traffic = 1 Gbit/s (so far we have worked with a dataset expressed in CDR units). Then, plot the three traffic traces in a single plot

2- Define function evaluate_cost()that takes in input ground-truth, ANN-predicted and LSTM-predicted traffic traces (scaled as in task 8a) and two cost parameters alphaand betafor over/under-provisioning and returns cost of over/under-provisioning for the ANN and LSTM cases, assuming a given resource allocation policy

3-Use function evaluate_cost()with given over/under-provisioning cost weights using ground-truth, ANN-predicted and LSTM-predicted traffic traces above; plot results in a 3D graph



This repository contains in-class activities for the "Network Measurement and Data Analysis" course taught by [Prof. Redondi](https://scholar.google.com/citations?user=8ka5NmUAAAAJ&hl=en) and [Prof. Musumeci](https://scholar.google.it/citations?user=RsM0KB0AAAAJ&hl=it) at Politecnico di Milano.
