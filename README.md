# Action Recognition with CNN
In this project, Convolutional Neural Networks (CNN) are trained to classify images and videos using Pytorch. 

# Dataset
Used UCF101 data `http://crcv.ucf.edu/data/UCF101.php` but took only 10 classes of 101 classes. Each clip has 3 frames and each frame is 64 ∗ 64 pixels. The label of clips are in `q3_2_data.mat`. `trLb` are labels for training clips and `valLb` are labels for validation clips. 

CNN is first trained for action classification for each image. Then, CNN is trained using 3D convolution to classify each clip as a video rather than an image

# Kaggle Competitions
1. Action recognition by CNN on images - ranked 10 - `http://www.kaggle.com/c/cse512springhw3`
2. Action recognition by CNN on videos - ranked 32 - `http://www.kaggle.com/c/cse512springhw3video`
