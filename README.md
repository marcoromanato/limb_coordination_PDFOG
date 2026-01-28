## Limb coordination - PD FOG
Repository containing data and code to reproduce the figures and run scripts for the preprint:

Marco Romanato,* Antonio Carlos Costa,* ... Carine Karachi, Claire Wyart, Brian Lau, Marie-Laure Welter (2026). 
Body-segment coordination as a new predictor of freezing of gait in people with Parkinson’s disease. 

Calculations were performed using Python 3.12.11 and the following packages: 
numpy 2.3.2, pandas 2.3.2,
scipy 1.16.1, seaborn 0.13.2, 
scikit-learn 1.7.1, h5py 3.14.0,

##### Dataset
The h5 file 'raw_gait_cycle_kinematics.h5' contains the used dataset: 
Per each trial, participant and condition the dataset contains:   
    -  X_: the segmented trajectories (x, y, z) of the considered markers
    -  accel_: the segmented accelerations (x, y, z) of the considered markers
    -  ['data'].keys(): labels indicating the condition, participant

