# DeepCU
DeepCU: Integrating Both Common and Unique Latent Information for Multimodal Sentiment Analysis

    
### Dependencies / Notes
DeepCU is written in python3 with some code fragments copied from DCGAN implementation from Carpedm20.
  - The code is developed with Python 3.6 and TensorFlow 1.12.0 (with GPU support) on Linux
  - For reasons of my convenience, `data_dir` is required to be `data_dir = ../../data` -- errors might pop-up when other directories are used.
  - The experiments (main.py) - loads pretrained model and executes test (i.e. prediction with our trained model). If you wish to train on  your own data, please edit as deep_cu.train(FLAGS).
  

