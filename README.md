# Pytorch-Challenge-Model
My final submission for the Facebook Pytorch challenge

# My thoughts around how i implemented the model
I tried different architectures like ResNet 34,50,101 , Vgg 16,19 and DenseNet 161. The best performance architecture was DenseNet with 3 Hidden layers for the fully connected classifier. I didnt add a dropout layer because the dataset wasnot big enough and actually dropout decreased performance. I believe it decreased performance because its like an early burden on the network in the begining but then the networks learn how to strive through having less parameters and how to shape the best possible outcome through this bottleneck. 

# My thanks to Facebook and Udacity for this great opportunity
I learned alot about Pytorch framework and it actually became my favorite Framework

