🐱🐶 Cats vs Dogs Image Classification using MobileNetV2

This project applies Transfer Learning using the MobileNetV2 model from TensorFlow Hub to classify images of cats and dogs. MobileNetV2 is a lightweight CNN architecture that is efficient and accurate, making it suitable for real-time image classification tasks.

📌 Features

Used MobileNetV2 feature extractor (https://tfhub.dev/google/tf2-preview/mobilenet_v2/feature_vector/4).

Preprocessed images: resized to 224x224, normalized pixel values, and applied data augmentation.

Fine-tuned the pre-trained MobileNetV2 on the cats vs dogs dataset.

Achieved 0.98 accuracy on validation set.

Implemented in Google Colab for training and evaluation.

🛠️ Technologies Used

Python

TensorFlow 2.x / Keras

TensorFlow Hub (MobileNetV2)

NumPy & Pandas

Google Colab

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/cats-vs-dogs-classification.git


Open the notebook in Google Colab.

Run all cells to load MobileNetV2, train the model, and evaluate accuracy.

📊 Results

Validation Accuracy: 0.98


📚 Learnings

How to use pre-trained models from TensorFlow Hub.

Transfer learning improves accuracy while saving computation.

Importance of input resizing (224x224) for MobileNet models.

🔮 Future Improvements

Experiment with other models from TensorFlow Hub (EfficientNet, Inception).

Deploy model as a web application using Flask/Streamlit.

Try real-time classification using a webcam feed.
