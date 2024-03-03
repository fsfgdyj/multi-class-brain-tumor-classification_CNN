This README outlines the motivation, objectives, and methodology for developing a deep learning model for brain tumor classification from MRI scans. The techniques employed address the challenges of imbalanced datasets, ensuring a fair and accurate model. For detailed implementation steps, please refer to the documentation.Feel free to contribute, share insights, or collaborate to enhance the accuracy and versatility of the model. Together, we can make significant strides in medical image analysis and computer vision.Deep learning-based brain tumor classification from brain magnetic resonance imaging (MRI) is asignificant research problem. The research problem encounters a major challenge. The training datasets used to develop deep learning algorithms could be imbalanced with significantly more samples for one type of tumor than others. This imbalance in the training dataset affects the performance of tumor classification using deep learning models as the classifier performance gets biased towards the majority class.The objective of this study is to develop a model for detecting and classifying objects in images.The accurate identification of objects in images has various applications in computer vision and object recognition tasks. This methodology outlines the steps taken to build and train aconvolutional neural network (CNN) model for this purpose.

Screenshots (Results & Web Interface)

![web1](https://github.com/jayd-bit/multi-class-brain-tumor-classification_CNN/assets/132098211/5f560076-b272-4f80-9768-032895bf1674)

![web2](https://github.com/jayd-bit/multi-class-brain-tumor-classification_CNN/assets/132098211/779f6476-ef39-4a1d-8aff-5a1bcd7981a4)

![web3](https://github.com/jayd-bit/multi-class-brain-tumor-classification_CNN/assets/132098211/79f4eccd-be36-4b76-ae07-8335b89609c6)

![web4](https://github.com/jayd-bit/multi-class-brain-tumor-classification_CNN/assets/132098211/38236121-956c-4116-854b-fb71f9b5068a)

Classifier Evaluation

Loss Grapf
![loss_metrics](https://github.com/jayd-bit/multi-class-brain-tumor-classification_CNN/assets/132098211/cf453ded-0a60-43a9-839d-d3558e569e49)

Accuracy etrics
![accuracy_metrics](https://github.com/jayd-bit/multi-class-brain-tumor-classification_CNN/assets/132098211/c4221dc7-8421-4c48-8247-bb00860935eb)

Confusion Matrix on Test set
![cm](https://github.com/jayd-bit/multi-class-brain-tumor-classification_CNN/assets/132098211/0f47985b-745a-4945-9818-dbc25beeeb3b)

Requirements
Python 3 is required.

Computational Specifications
Project done using Google Colab with follwing specifications:

Ubuntu 18.04 64-bit OS
12 GB DDR4 RAM
16 GB NVidia Tesla P100 GPU
40 GB of Non-Persistent Storage
Library Requirements
We'll be using the following libraries to complete our classification problem:

Numpy - For linear algebra operations
Torch - Pytorch Deep Learning Framework
OS - To use Operating System methods
Random - To set random seed at specific places where random operations take place just so it happens the same way everytime it is executed
Pandas - To create DataFrame, CSV files, etc
Time - To perform date time operations
Seaborn - For sophisticated visualization
Pickle - To save and load binary files of our training data
Scikit-Learn - Machine learning framework. We have used this for evaluating our Classifier and for cross-validation split
Matplotlib - To visualize images, losses and accuracy
Google Colab Drive - To mount Google Drive so we can perform storage and loading operations using it (Only available on Google Colab)
The above mentioned libraries comes pre-installed and pre-configured with Google Colab.

Install the required libraries on your computer using the pip package manager.

For pip version 19.1 or above:

pip install -r requirements.txt --user
or

pip3 install -r requirements.txt --user
Pytorch
Follow the steps for installation given in the official website of Pytorch.

Research Papers
Multi-class classification of brain tumor types from MR images using EfficientNets

A Deep Learning-Based Framework for Automatic Brain Tumors Classification Using Transfer Learning

Deep Residual Learning for Image Recognition (ResNet)

Documentations
Pytorch
Future Scopes
Brain Tumor segmentation using GANs.
Brain Tumor detection using Object Detection for localization of tumor in a given MRI image of the brain.
Improve existing classification model and web interface
