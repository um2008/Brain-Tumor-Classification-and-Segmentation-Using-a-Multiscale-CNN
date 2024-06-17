We implemented the research paper "A Deep Learning Approach for Brain 
Tumor Classification and Segmentation Using a Multiscale Convolutional 
Neural Network" (Francisco Javier Díaz-Pernas, Mario Martínez-Zarzuela, Míriam 
Antón-Rodríguez, and David González-Ortega).

This paper presents a model of fully automatic brain tumor segmentation and 
classification using a Deep Convolutional Neural Network (CNN), incorporating a 
multiscale approach. Unlike prior works, input images in three spatial scales are fed 
into our method along different processing pathways to mimic the intrinsic operation 
of the Human Visual System. 

The proposed neural model can analyze MRI images containing three types of 
tumors: meningioma, glioma, and pituitary tumor, across sagittal, coronal, and axial 
views; furthermore, images do not have to be preprocessed to remove skull or 
vertebral column parts in advance. The performance of our method is tested on a 
publicly available MRI image dataset consisting of 3064 slices from 233 patients. 
Compared to classical machine learning and deep learning, the accuracy in tumor 
classification attains a value of 0.973, which is significantly higher than other 
approaches using the same database. However, due to technical limitations, such as 
average computational powers, we could not train the data fully and therefore 
received an accuracy of 0.831.
