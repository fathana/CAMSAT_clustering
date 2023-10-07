# CAMSAT clustering for speaker recognition/verification

This repository is for our paper entitled "CAMSAT: Augmentation Mix and Self-Augmented Training Clustering for Self-Supervised Speaker Recognition" currently under review.

Code of our experiments as well as all pseudo-labels will be available upon acceptance of our paper. 

- The general process for training our clustering generated pseudo-label-based self-supervised speaker embedding networks: ![](/process_pseudo_label_based_speaker_embedding_training.png)

- The pipeline of our proposed CAMSAT clustering method depicting the data flow and the different losses employed for clustering: ![](/CAMSAT_diagram.png)
  We constrain the predictions of the MLP-based neural network to remain unchanged under local perturbations and data augmentations while enforcing symmetry w.r.t. augmentations (red arrows). Information maximization refers 
  to maximizing the information-theoretic dependency between data and their assignments (predictions).
