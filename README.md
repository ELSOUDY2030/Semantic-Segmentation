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
```  
 https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge 
```

<div align="center">
    <img src="https://github.com/ELSOUDY2030/Semantic-Segmentation/blob/main/image/ezgif.com-gif.gif" width="500" height="500">
</div>

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
 - [OpenCV](https://docs.opencv.org/4.x/d5/de5/tutorial_py_setup_in_windows.html)
 - [Matplotlib](https://matplotlib.org/stable/users/installing/index.html)



##### Run
Run the following command to run the project:
```
Semantic Segmentation for Self Driving Cars.ipynb
```

### Training results and weights  

After training for 200 epochs on images with a size of 512x512, targeting the semantic segmentation of 12 masks and backgrounds using the dice loss function, the following results were achieved:

- Dice Coefficient: 0.9389
- Accuracy: 0.9571
- Loss: 0.1424
These results indicate a high level of accuracy and a strong dice coefficient, demonstrating the effectiveness of the trained model in segmenting the 12 masks and backgrounds in the images.

<div align="center">
    <img src="https://github.com/ELSOUDY2030/Semantic-Segmentation/blob/main/image/ezgif.com-gif-maker%20(3).gif" width="500" height="500">
</div>

## Get in Touch

[<img alt="alt_text" width="30px" src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Whatsapp2_colored_svg-512.png" />](https://wa.me/+201279548818)
&nbsp;&nbsp;
[<img alt="alt_text" width="30px" src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Linkedin_unofficial_colored_svg-512.png" />](https://www.linkedin.com/in/mohammad-nomer/)
&nbsp;&nbsp;
[<img alt="alt_text" width="30px" src="https://cdn4.iconfinder.com/data/icons/social-media-logos-6/512/112-gmail_email_mail-256.png" />](mailto:mohammadnomer2030@gmail.com)
&nbsp;&nbsp;



## Give Feedback

Please share your feedback on how I can improve and any ideas to enhance the model. I'm eager to receive any advice that can help me develop my skills.

&nbsp;&nbsp;

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Lobster&size=50&duration=4000&pause=300&color=FFC107&background=FFFFFF00&center=true&vCenter=true&width=1200&height=240&lines=Thank+you" alt="Typing SVG" /></a>




