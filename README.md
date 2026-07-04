###### Hand Gesture Recognition using CNN



**SkillCraft Technology - Machine Learning Internship**

Task 04



This project implements a Hand Gesture Recognition System using a Convolutional Neural Network (CNN). The model is trained on the LeapGestRecog dataset to classify different hand gestures from grayscale images.



The project demonstrates the complete deep learning workflow, including image preprocessing, model training, evaluation, visualization of training performance, and gesture prediction.





###### Project Overview



The objective of this project is to develop a CNN model capable of accurately recognizing different hand gestures. Such systems are widely used in:



* Human-Computer Interaction
* Touchless Control Systems
* Virtual Reality
* Sign Language Recognition
* Smart Automation





###### Features



* Image preprocessing and normalization
* CNN-based gesture classification
* Training and validation accuracy visualization
* Training and validation loss visualization
* Sample gesture predictions
* Saved trained model for future use





###### Dataset



This project uses the LeapGestRecog dataset from Kaggle.



Dataset Link:



https://www.kaggle.com/datasets/gti-upm/leapgestrecog



Note: The dataset is not included in this repository because of its large size.





###### Technologies Used



* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn





###### CNN Model



###### Input Image Size:



64 × 64 pixels





###### Gesture Classes:



* Palm
* L
* Fist
* Fist\_Moved
* Thumb
* Index
* OK
* Palm\_Moved
* C
* Down





###### Project Workflow



* Download the LeapGestRecog dataset.
* Resize all images to 64 × 64.
* Normalize pixel values.
* Split data into training and testing sets.
* Build a CNN model.
* Train the model.
* Evaluate model performance.
* Plot accuracy and loss graphs.
* Predict sample hand gestures.
* Save the trained model.





###### Results



The CNN achieved approximately 99–100% test accuracy on the dataset.



Generated outputs include:



* Dataset samples
* Training accuracy graph
* Training loss graph
* Sample predictions
* Trained CNN model





###### Project Structure



SCT\_ML\_4/

│── Hand\_Gesture\_Recognition.ipynb

│── README.md

│── requirements.txt

│── hand\_gesture\_model.h5

│── accuracy\_graph.png

│── loss\_graph.png

│── sample\_predictions.png

│── dataset\_samples.png





###### Installation



**Clone the repository:**



git clone https://github.com/AmruthaRaju24/SCT\_ML\_4.git



**Install the required libraries:**



pip install -r requirements.txt



**Run the notebook:**



jupyter notebook Hand\_Gesture\_Recognition.ipynb





###### Output Images



**Dataset Samples**

!\[Samples](dataset\_samples.png)



**Training Accuracy**

!\[Accuracy](accuracy\_graph.png)



**Training Loss**

!\[Loss](loss\_graph.png)



**Sample Predictions**

!\[Predictions](sample\_predictions.png)







###### Future Improvements



* Improve robustness under different lighting conditions.
* Expand the dataset with more gesture categories.
* Deploy the model as a real-time webcam application.
* Optimize the model for mobile and edge devices.





###### Acknowledgements



SkillCraft Technology

Kaggle (LeapGestRecog Dataset)

TensorFlow/Keras Documentation

