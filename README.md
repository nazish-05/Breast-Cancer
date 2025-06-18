# Breast-Cancer
This project is a web-based image classification tool built to detect Breast Cancer using deep learning techniques. Powered by TensorFlow, Keras, and Gradio, the application enables users to upload breast histopathology or MRI images and get predictions indicating whether the tissue is Benign or Malignant.

The system features a model switcher that cycles through multiple pre-trained models—Custom CNN, ResNet50, and MobileNetV2 on each prediction request, allowing users to observe and compare the performance of different architectures on the same input. Uploaded images are preprocessed by resizing to a standard input shape, normalizing pixel values, and converting to tensors compatible with the models.

Once processed, the app displays:

  The predicted class (Benign/Malignant)

  The confidence score of the prediction

  The model name used for the prediction

The Gradio interface is designed for ease of use and includes:

   Image upload box

   Prediction button

   Clear/reset button

   Real-time output display including label and probability

This notebook and app serve as an interactive demonstration for medical image classification, model comparison, and AI-assisted diagnosis, making it valuable for research, education, and clinical experimentation in cancer detection.
![Screenshot (1136)](https://github.com/user-attachments/assets/656312ab-e6da-417e-aa4a-53a2b1fd8924)
![Screenshot (1137)](https://github.com/user-attachments/assets/944c4ea5-0f35-428b-9f8a-400c8cfcd898)
![Screenshot (1138)](https://github.com/user-attachments/assets/578be1a2-d1b8-4190-a5d8-7e990fa9e82f)


