# Cat and dogs classifier
Image classification project developed with **Python, TensorFlow, and Keras**.
I used the **MobileNetV2** model pre-trained on ImageNet for this project.


This project was developed as part of my studies in **Machine Learning and Deep Learning**.


During development, I practiced:


- Image classification
- Convolutional Neural Networks (CNNs)
- Transfer Learning
- MobileNetV2
- Image preprocessing
- Training, validation, and testing
- Model evaluation
- Prediction on new images


In this project, I replaced the classification layer with a layer that classifies two classes:


- Cats
  
- Dogs

**USE OF AI**

AI tools were used to support the development process, primarily to clarify concepts, investigate errors, and review parts of the implementation.

**DATASET**

The database was divided into:

70% → training
15% → validation
15% → testing


This is the link to the dataset I downloaded for the project: https://www.microsoft.com/en-us/download/details.aspx?id=54765

**TRAINING**

The model was trained using:

Optimizer: *Adam*

Loss: Sparse Categorical Crossentropy

Metric: Accuracy

Epochs: 10

Batch size: 32


**RESULTS**

Train_accuracy: 0.9977 = 99,7%

Val_accuracy: 9858 = 98,58%

Test_accuracy: 0.9896055459976196 = 98,96%


**VALIDATION**

![Gráfico de validação](https://github.com/user-attachments/assets/ef81aa9e-5c88-4d0f-bc06-578c76babebc)

**Fine-tuning**

The dataset used for fine-tuning was the same one used for transfer learning.
