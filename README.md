Motivation:
The motivation behind this project is to address the crucial issue of brain tumor classification using deep learning techniques on MRI scans. Medical image analysis, particularly in the field of neurology, can greatly benefit from accurate and efficient tools for tumor detection. The primary motivation is to contribute to advancements in medical imaging, leading to early and precise diagnosis of brain tumors.

Objectives:
Develop a Deep Learning Model:

Create a robust convolutional neural network (CNN) model for brain tumor classification from MRI scans.
Achieve high accuracy and reliability in distinguishing between different types of brain tumors.
Address Imbalanced Datasets:

Tackle the challenge of imbalanced datasets, where one type of tumor may be overrepresented in the training data.
Implement strategies to ensure fair and accurate classification across all tumor types.
Documentation:

Provide detailed documentation outlining the implementation steps, model architecture, and training procedures.
Facilitate easy replication and understanding of the developed model for researchers and practitioners.
Methodology:
Data Preprocessing:

Standardize and preprocess MRI scans to ensure uniformity in input data.
Augment the dataset to increase variability and enhance model generalization.
Model Architecture:

Design a convolutional neural network (CNN) architecture suitable for medical image analysis.
Optimize the model to effectively capture features indicative of different tumor types.
Addressing Imbalanced Data:

Implement techniques such as oversampling, undersampling, or the use of class weights to handle imbalanced datasets.
Ensure the model does not exhibit bias towards the majority class.
Training and Evaluation:

Split the dataset into training, validation, and test sets.
Train the model using appropriate loss functions and optimization algorithms.
Evaluate the model on the test set, considering metrics like accuracy, precision, recall, and F1 score.
Documentation and Collaboration:

Maintain comprehensive documentation for the entire project, including code comments, explanations, and references.
Encourage collaboration by inviting contributions, insights, and feedback from the community to enhance the model's accuracy and versatility.
Contribution:
Your contributions, insights, and collaboration are welcome to collectively advance the field of medical image analysis. Feel free to explore the documentation, provide feedback, suggest improvements, or share your expertise to make significant strides in brain tumor classification using deep learning. Together, we can contribute to the improvement of healthcare through innovative computer vision solutions.






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
