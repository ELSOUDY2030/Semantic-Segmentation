# Semantic-Segmentation
## Semantic Segmentation for Self-Driving Cars using Unet
The primary objective of this project is to utilize Tensorflow in training an artificial neural network for semantic segmentation. This network will be used to identify and label road pixels in images captured by a self-driving car simulator called CARLA.

<div align="center">
    <img src="https://github.com/ELSOUDY2030/Semantic-Segmentation/blob/main/image/ezgif.com-gif-maker%20(2).gif" width="500" height="500">
</div>

### Data set
This dataset includes images and associated labeled semantic segmentations obtained from the CARLA self-driving car simulator. It was created as a component of the Lyft Udacity Challenge. This dataset serves as a valuable resource for training machine learning algorithms to recognize semantic segmentation, such as identifying cars and roads within an image.

The dataset comprises five sets, each containing 1000 images along with their corresponding labels.

The link Data:
    '''
    https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge
    '''

```  
...
 The main difference is that there is multiple prediction layers: one for each upsampling layer. 
 Like the U-Net, the FPN has laterals connection between the bottom-up pyramid (left) and the top-down pyramid (right).
 But, where U-net only copy the features and append them, FPN apply a 1x1 convolution layer before adding them. 
 This allows the bottom-up pyramid called “backbone” to be pretty much whatever you want.  
...
```

<div align="center">
    <img src="https://github.com/ELSOUDY2030/Semantic-Segmentation/blob/main/image/ezgif.com-gif.gif" width="500" height="500">
</div>
