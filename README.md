# Hybrid_SVM_model
Accurate colon cancer diagnosis and Lung Cancer diagnosis is crucial for effective
treatment and patient care. This study introduces a hybrid approach that combines the power of deep learning and machine
learning to enhance colon and lung cancer detection. Our project model utilizes ResNet-50 Convolutional Neural Network (CNN) and DenseNet121 features for
robust feature extraction (FE) and employs Kernel Support Vector Machine (SVM) analysis with meticulous kernel selection. This
unique combination optimizes the model’s ability to discriminate
between benign and malignant regions within colon cancer histopathology images and Cancerous , non_cancerous and Scc in lung cancer.

Dataset Details
This dataset contains 25,000 histopathological images with 5 classes. All images are 768 x 768 pixels in size and are in jpeg file format.
The images were generated from an original sample of HIPAA compliant and validated sources, consisting of 750 total images of lung tissue (250 benign lung tissue, 250 lung adenocarcinomas, and 250 lung squamous cell carcinomas) and 500 total images of colon tissue (250 benign colon tissue and 250 colon adenocarcinomas) and augmented to 25,000 using the Augmentor package.
There are five classes in the dataset, each with 5,000 images, being:

Lung benign tissue
Lung adenocarcinoma
Lung squamous cell carcinoma
Colon adenocarcinoma
Colon benign tissue
link : [Lung and colon cancer Histopathological Images](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images)
