# 01_ZUM_BrainTumorDetectionCNN

## Project Objective
Detect tumors by using MRI scans of a brain. The project objective is to construct a convolutional neural network for classification problem solving.

## Project Description
The proposed technique has used CNN to identify and categorize the tumor from brain images of the brain. The main difference between the main channel of the neural network with the normal neural network is that it is able to automatically and locally extract the feature from each image.

Due to the results of CNN on the dataset, in order to improve the proposed method. Machine learning algorithm is used to feature extraction. 

The algorithm used was the clustering algorithm applied on data set, and then the images are applied to the CNN. The results showed that the proposed method has been successful. The purpose of extracting the property before applying to the CNN is that in some images fatty masses are considered as tumors, or in some images the tumor is mistakenly considered to be fat and should have increased medical error. Extracting the attribute initially and before applying the CNN leads to improved network accuracy and increased accuracy.

## Data
The dataset is taken from the [open-source](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection).


![N22](https://user-images.githubusercontent.com/18750837/206770190-49946666-310e-40cc-8230-7fa00a81b4f8.JPG)

Sources:
- Amin, J., Sharif, M., Raza, M., Saba, T., & Anjum, M. A. (2019). Brain tumor detection using statistical and machine learning method. Computer methods and programs in biomedicine, 177, 69-79.

- George, D. N., Jehlol, H. B., & Oleiwi, A. S. A. (2015). Brain tumor detection using shape features and machine learning algorithms. International Journal of Advanced Research in Computer Science and Software Engineering, 5(10), 454-459.

- Sharma, K., Kaur, A., & Gujral, S. (2014). Brain tumor detection based on machine learning algorithms. International Journal of Computer Applications, 103(1).
