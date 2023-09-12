# Capsule-detection

Drug prescription and inventory management are very important tasks for 
safe drug dispensing, while promptness and accuracy are also very 
essential .Approximately 1000 types of pills are handled in large 
hospitals. The pills used by the patients are changed depending on the 
patient's degree of improvement. What happens if the prescribed pill has a 
manufacturing defect ?

# METHODOLOGY
Thinking on its way to solve the given problem statement we came up with an 
solution which will overcome all the described problem in detection of pills. 
The solution to given problem is provided with computer vision models and we 
have performed some of the computer vision techniques in order to give 
solution to the given problem statements they are as follows ;
I. Image classification using Machine Learning.
II. Object Detection using computer vision model.
III.Semantic Segmentation using FCN.

# Dataset
The dataset contains 961 images with 3 different classes such as contaminated, 
crack and good images of pills . These images are preprocessed using AutoOrient and Resize techniques. Agumentation steps like horizontal flip, rotation, 
saturation, brightness and blur. After applying Pre processing and Agumentation 
techniques now the dataset become more concise with 2161 images . And this 
dataset is divided as 70% (1.8k) for training, 20%(300) for validation,10%(61) 
for testing. This dataset is sufficient enough to train the model and achieving 
better accuracy


I have used the InceptionV3 model for classification of pill image such as 
contaminated, crack and good . I have also tested the using the VGG16 model 
one of the pretrained model in machine learning .But comparatively 
InceptionV3 model helps in attaining better accuracy of 93.10.
