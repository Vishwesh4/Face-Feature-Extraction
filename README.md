# Face-Feature-Extraction

This is a CNN which takes in 96*96 images from kaggle-dataset and predictes 15 landmark points:
- [left_eye_center_x]                                                   
- [left_eye_center_y]                                                      
- [right_eye_center_x]                                                   
- [right_eye_center_y]                                                     
- [left_eye_inner_corner_x]                                                
- [left_eye_inner_corner_y]                                                
- [left_eye_outer_corner_x]                                               
- [left_eye_outer_corner_y]                                                
- [right_eye_inner_corner_x]                                               
- [right_eye_inner_corner_y]                                               
- [right_eye_outer_corner_x]                                               
- [right_eye_outer_corner_y]                                               
- [left_eyebrow_inner_end_x]                                               
- [left_eyebrow_inner_end_y]                                               
- [left_eyebrow_outer_end_x]                                               
- [left_eyebrow_outer_end_y]                                              
- [right_eyebrow_inner_end_x]                                             
- [right_eyebrow_inner_end_y]                                             
- [right_eyebrow_outer_end_x]                                              
- [right_eyebrow_outer_end_y]                                              
- [nose_tip_x]                                                             
- [nose_tip_y]                                                           
- [mouth_left_corner_x]                                               
- [mouth_left_corner_y]                                                  
- [mouth_right_corner_x]                                                   
- [mouth_right_corner_y]                                                  
- [mouth_center_top_lip_x]                                              
- [mouth_center_top_lip_y]                                              
- [mouth_center_bottom_lip_x]                                             
- [mouth_center_bottom_lip_y]

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Libraries needed

```
numpy
keras
tensorflow
cv2
matplotlib
pickle
h5py
string
os
```
## Running the tests

You can download the dataset from Kaggle website(https://www.kaggle.com/c/facial-keypoints-detection)

![Alttext](https://raw.github.com/Vishwesh4/Face-Feature-Extraction/master/images/sample_images.png)

Run Feature_Extraction-Keras.ipynb

## Model

The following model has been inspired from the research paper by Namish(https://arxiv.org/pdf/1710.00977.pdf)
![Alttext](https://raw.github.com/Vishwesh4/Face-Feature-Extraction/master/images/cnn_model.png)

### Results

The Model gets an acc of 0.95 on training set and 0.79 on cv set

![Alttext](https://raw.github.com/Vishwesh4/Face-Feature-Extraction/master/images/training.png)
![Alttext](https://raw.github.com/Vishwesh4/Face-Feature-Extraction/master/images/cv.png)
