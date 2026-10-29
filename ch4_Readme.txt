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