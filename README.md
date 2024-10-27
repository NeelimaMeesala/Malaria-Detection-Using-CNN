# Malaria-Detection-Using-CNN
Malaria is a serious and potentially life-threatening disease caused by parasites that are transmitted to people through the bites of infected mosquitoes. It is a major public health problem, and can lead to severe illness and death if left untreated. Early diagnosis is essential as it can help save the severity or deteriorating health condition. One approach that we can use in the diagnosis of malaria is the use of convolutional neural networks (CNNs), which are a type of artificial intelligence model that is particularly well-suited for image classification tasks. CNNs can be trained to recognize patterns in images of infected blood cells and make a diagnosis based on those patterns.

The dataset that we was used contains about 27560 images consisting 13780 parasitized images and 13780 healthy cell images. 

**Pre-Processing the Data:**
Pre-processing image data before creating a CNN model is an important step in the machine learning process. It involves cleaning and normalizing the data, extracting relevant features, Pre-processing helps to improve the quality and consistency of the data, which can lead to a more accurate and effective model. In Pre-Processing the image data is converted data NumPy arrays so that the model can understand it and extract the features. Also, as the images vary in size I have resized them to a common size. 

**CNN Architecture:**
The Model consists of an input Layer, 3 Convolutional Layers, 3 Pooling Layers, 3 Normalization Layers and 3 Dropout Layers. 

**Accuracy and Saving the model:**
In the final step, evaluated the models performance and changed the parameters when required and finally saved the model to deploy it.
