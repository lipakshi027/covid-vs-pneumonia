# covid-vs-pneumonia
COVID-19 Detection- Flask-App-based on chest x rays

COVID-19, or more commonly known as the Novel Coronavirus disease is a highly infectious disease that appeared in China towards the end of 2019. This disease is caused by SARS-CoV-2, a virus that belongs to the large family of coronaviruses. The disease first originated in Wuhan, China in December 2019 and soon became a global pandemic, spreading to more than 213 countries.
The most common symptoms of COVID-19 are fever, dry cough, and tiredness. Other symptoms that people may experience include aches, pains, or difficulty in breathing. Most of these symptoms show signs of respiratory infections and lung abnormalities which can be detected by radiologists.
Thus, it is possible to use Machine Learning algorithms to detect the disease from images of Chest X-rays and CT scans. Automated applications can be created to help support radiologists. This article is an attempt to use four Deep Learning algorithms, namely: VGG16, ResNet50, InceptionV3 and Xception.

# Dataset
For dataset and weights https://drive.google.com/drive/folders/1pTA9X2zQdyzIENxS3VA7lbJzKVT_nyYd?usp=sharing


Chest X-ray images (1000 images) were obtained from: https://github.com/ieee8023/covid-chestxray-dataset



# Technical Concepts

ImageNet is formally a project aimed at (manually) labeling and categorizing images into almost 22,000 separate object categories for the purpose of computer vision research.


ResNet50 ResNet-50 is a convolutional neural network that is 50 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. Unlike traditional sequential network architectures such as AlexNet, OverFeat, and VGG, ResNet is instead a form of “exotic architecture” that relies on micro-architecture modules.

VGG16 is a convolutional neural network model proposed by K. Simonyan and A. Zisserman from the University of Oxford in the paper “Very Deep Convolutional Networks for Large-Scale Image Recognition”. The model achieves 92.7% top-5 test accuracy in ImageNet, which is a dataset of over 14 million images belonging to 1000 classes.

Inception-V3 is a convolutional neural network that is 48 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 299-by-299.

Xception is a convolutional neural network that is 71 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 299-by-299.
