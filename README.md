Title :  CNN-Driven Classification of Cervical Cancer from Medical Imaging Data

grpou information : 
1. Nafisa Saiyara Aranti (2022-1-60-060)
2. Sirajam Munira Naba (2022-2-60-021)
3. Shaosan Midha Rahman (2021-2-50-001)
4. Md Touhidul Islam Alif (2022-1-60-142)


Description of the problem and dataset:

The Multi-Cancer dataset from Kaggle is designed for medical image classification and contains histopathological images spanning 8 main cancer types and 26 subclasses. In this project, the focus is on classifying cervical cancer from the dataset. The problem is challenging due to the multi-class nature of the data, potential class imbalance, and variations in image quality. Accurate classification is highly important since early detection of cervical cancer can significantly improve patient outcomes. This dataset provides a strong foundation for applying deep learning and transfer learning approaches, such as CNNs, to develop reliable models for medical diagnosis.


The implementation and training of the Convolutional Neural Network (CNN) model were carried out on the Kaggle platform, utilizing its cloud-based GPU resources for efficient computation


Summary of experiments and methodology:

In this study, multiple deep learning approaches were implemented and evaluated for cervical cancer image classification. All experiments were conducted on the Kaggle platform using GPU acceleration. Transfer learning was applied with pretrained models such as MobileNet and VGG, where the final classification layers were fine-tuned for the dataset. In addition, a custom Convolutional Neural Network (CNN) was designed and trained from scratch to serve as a baseline. To further enhance performance, a hybrid CNN-SVM model was developed, where the CNN acted as a feature extractor and the final classification was performed using a Support Vector Machine (SVM). This methodology enabled a comparative analysis of pretrained networks, a custom CNN, and a hybrid deep learning–machine learning approach for cervical cancer detection.

