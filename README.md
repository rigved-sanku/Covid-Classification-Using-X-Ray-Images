# Covid-Classification-Using-X-Ray-Images
Built a Convolution Neural Network Model to predict Positive or Negative Covid-19 cases from X ray images of patient's lungs within a accuracy around 93% of training set and 98% accuracy with testing set using Keras libraries.

A CNN Network for Binary classification 
![image](https://user-images.githubusercontent.com/63362412/123130372-599cc400-d46a-11eb-9ede-f2c01fcf5597.png)

# An example of X-ray image in the dataset
![test_image](https://user-images.githubusercontent.com/63362412/123131749-a03eee00-d46b-11eb-970b-f2e4624e72ee.jpeg)
**X-Ray image of a Covid Positive patient**


# Technical Aspect

### 1. Data Augmentation and
#### (i) Data Preprocessing
 * Rescaling pixel values to (0,1)
#### (ii) Data Augmentation
  * Rotated and Tilted Images
  * Zoomed Images
  * Horizontal Flip -Lateral Inversion
  
 ### 2. Convolution Neural Network
 * Input Layer (Input Image)
 * Convolution Layers (4)
 * Pooling Layers (4)
 * Flattening Layer 
 * Fully Connected Layer
 * Output Layer

### 3. Activation Functions :
     * Convolution Layers - ReLu
     * Output Layer - Sigmoid









