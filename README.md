# Chapter 4: Driving heterogeneity action chains

Code, small data files, and figures accompanying this chapter. The original folder structure is preserved.

## Software

The analysis uses Jupyter notebooks and Python. Dependencies and execution paths have not yet been validated. Consult the notebooks and scripts for imports and input paths.

## Data included and omitted

Data files of at most 10 MB (10,000,000 bytes) are included. Larger files are omitted; workflows requiring those files need the original data before they can run. No replacement or sampled data has been generated.

| Omitted file | Size (MB) |
| --- | ---: |
| `Data/Car101_S1.csv` | 27.12 |
| `Data/Car101_S2.csv` | 59.45 |
| `Data/Car101_S3.csv` | 38.35 |
| `Data/Car80_S1.csv` | 11.20 |
| `Data/trajectories_0400_0415.txt` | 179.30 |
| `Data/trajectories_0500_0515.txt` | 220.09 |
| `Data/trajectories_0515_0530.txt` | 249.04 |
| `Data/trajectories_0750am_0805am.txt` | 167.64 |
| `Data/trajectories_0805am_0820am.txt` | 199.24 |
| `Data/trajectories_0820am_0835am.txt` | 215.16 |

## Original chapter instructions

Input data: 
NGSIM dataset, including trajectories_0400_0415.txt, trajectories_0500_0515.txt, trajectories_0515_0530.txt, trajectories_0750am_0805am.txt, trajectories_0805am_0820am.txt, trajectories_0820am_0835am.txt

Script: 
1_data_preparation.ipynb: data preprocessing, filtering
2_segmentation.ipynb: Action phase segmentation, rule-based methods
3_driving_map.ipynb: visualization of the segmentation results, showing the driving profiles of indicidual drivers
4_heterogeneity_index.ipynb: Action phase transition using Markov chain, heterogeneous traffic flow evaluation

Output
Data processing csv. files
Segmentation results: I80_total_states.csv, US101_total_states.csv
Heterogeneity index: I80_joint_transition_probs.csv, I80_mse_results.csv, I80_PROB.npy, US101_joint_transition_probs.csv, US101_mse_results.csv, US101_PROB.npy
