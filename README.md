# Recognize handwritten numbers in MINIST images


This is a project with C++11 and Python3.

Also use MINIST dataset to train model and save model to a *.npz file.

The model was used to recognize the number in the images. 

prj1 is used for testing that via using python call binary files of c++ compiled;

prj5 is a 4-layer MLP model, the model file was saved in p5_params.npz; 

prj6 is a 6-layer CNN model, the model file was saved in p6_params.npz;

For MLP, the test accuracy is greater than 96.1%, the sum of log(loss) is less than 4773.266. 

For CNN, the test accuracy is greater than 96.7%, the sum of log(loss) is less than 4749.440.
