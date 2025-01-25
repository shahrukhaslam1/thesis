This file contains the breif description of each code file that is used in this research 

'Ocular Disease Predicition'
File contains the EDA and initital runs of the model by taking sample of 200 images of each class

New_ODP(H, V Flip Data Augmentation)
This file contains execution of model after vertical and horizantal flips and defining criteria of reduction for Normal and diabetes Class

New_ODP(Data Augmentation)H,V,R
This file contains execution of Horizontal Vertical and Rotation of 10 degrees , it also include reduction criteria for Normal and Diabetes Class


'All ODP images File'
In this 'new_filtered_images.csv' is created which is used in CNN filtered Images file and the Final ODP file
This file is saving al the results into the preprocessed folder and that preprocessed folder is named as New Dataset
that contains all the images after Horizontal , Vertical Flip and , Rotation operation on those classes with less images
and downsampled images of Normal class by ration 2/3

'Final ODP'
In this file , final execution of model is present . The new_filterd_images file that is used in it was created in 
'All ODP images File' and new dataset is the folder where all orignal images and augmented images are store . 
Reason for doing this is to reduce the coplexity , instead of taking images from two different directores , one directory
that contains all the images both orignal and augmented could be used 



