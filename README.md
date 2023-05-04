# Speech-Emotion-DL
Classification of speech samples on basis of emotion and tone from RAVDESS dataset using prasodic and spectral features.

We have trained multiple models for achieving the required classification
task. Based on the class separability of emotional features we observed, we divided the training tasks into 2 categories, 1) with the full dataset, and 2) with only 4 of the 8
emotions being used for observation.

We also filtered the audio files on the basis of emotion strength (given in the file name
itself).
Maximum accuracies were achieved by: 
- MLP with sigmoid activation 92.21% (on time averaged features) in case of 4-label emotion detection tasks; 
- 1D CNN : 64.23% (on prasodic inputs again), in case of full data utilisation for training.
