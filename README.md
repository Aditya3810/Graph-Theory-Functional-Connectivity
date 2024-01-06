# Graph-Theory-Functional-Connectivity
# Appendix

## Structure
The repository is formatted in a way where the code is represented for scripting the CONN toolbox on MATLAB first.
The results for functional connectivity are then presented in an orderly fashion.
No significant Function Connectivity differences existed between MCI vs CN groups.

## Data
The resting-state fMRI data were collected using 3T scanners from different manufacturers as a part of a large-scale collaborative effort on the ADNI project (GE Medical System, SIEMENS, and Philips systems). 
At the same time, patients were advised to keep their eyes open, according to the ADNI protocol (http://adni.loni.usc.edu/).

## Graph Theory Results
Kindly refer to the project report for an extensive insight into Graph Theory Results.
They were not represented as a separate file in the repository due to numerical calculations of graph theoretical measures such as Global Efficiency, Local Efficiency, Clustering Co-efficiency, Cost, Degree, Betweenness Centrality, and Average Path Length.

Overview:
A graph adjacency matrix A was calculated for each subject by dividing the associated ROI-to-ROI Correlation (RRC) matrix r by a cost threshold (cost<0.15) (Nieto-Castanon, 2020; Whitfield-Gabrieli & Nieto-Castanon, 2012). 
To avoid scale-free networks, i.e., networks in which a few nodes have more edges than others, the cost threshold, which also displays network sparsity, was set to <0.15 (Maslov & Sneppen, 2002; Milo et al., 2002; Salvador et al., 2005). 
We set the p-FDR threshold for the analysis at 0.05. After that, several measures were computed from the resulting graphs (see Table 2) to address the properties of each ROI within the network and the entire network constructed using the ROIs.

Interesting Note: 
Based on the disconnection hypothesis, we selected 53 ROIs, supported by neuropathological AD data, showing that the distribution of pathological changes in AD patients' brains does not appear in a random or widespread uniform fashion but is rather selective and restricted to some brain areas or even some laminae within those
areas. These data highlight that the degeneration in AD is not global but rather specific to areas related to corticocortical connections (Lafleche & Albert, 1995; Lakmache et al., 1998; Pantel et al., 1999; Teipel et al., 1999).

## Project Report
Kindly refer to project report for detailed experimentation explanation and results.
