# Image-Scene-Classification

## 🌍 Intel Image Scene Classification

This project is a simple image classification task using a Convolutional Neural Network (CNN) in TensorFlow/Keras. It uses the **Intel Image Scene Classification dataset** which includes six natural scenes: `buildings`, `forest`, `glacier`, `mountain`, `sea`, and `street`.

## 📁 Dataset Structure

The dataset is organized into 6 folders, each representing a class:
Image Scene Classification:<br>
├── buildings/<br>
├── forest/<br>
├── glacier/<br>
├── mountain/<br>
├── sea/<br>
└── street/<br>



## 🔧 Tools Used
- Python
- TensorFlow & Keras
- Google Colab
- Matplotlib
- Google Drive for dataset storage

## 🚀 How It Works

1. Mount Google Drive and load the dataset.
2. Display one sample image from each of the 6 classes.
3. Prepare data using `ImageDataGenerator` with rescaling and validation split.
4. Build a simple CNN model with 2 convolutional layers.
5. Train the model for 10 epochs.
6. Plot training and validation accuracy.
7. Evaluate the model on the validation set.

## 🧠 Model Architecture

- Conv2D → MaxPooling2D  
- Conv2D → MaxPooling2D  
- Flatten → Dense → Dense (softmax)

## 📊 Results

- Training and validation accuracy are plotted after training.
- Final validation accuracy is printed.

## 📸 Sample Output

- 6 sample images shown with their class names before training
- Accuracy graph showing model performance

## 📂 Folder Structure in GitHub


#
## 🔗 Dataset Source

- Dataset used: Intel Image Classification  
- [Kaggle Dataset Link](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)

## ✅ To Run the Project

1. Upload the dataset to your Google Drive in the correct folder structure.
2. Open the notebook in Google Colab.
3. Run all the cells.
4. The model will train and evaluate the results visually.

---

## 🙌 Acknowledgment

Special thanks to **Kaggle** for the dataset and **Google Colab** for providing a free GPU environment.

---

## 💡 Future Improvements

- Add data augmentation for better generalization
- Use Transfer Learning (e.g., MobileNet, ResNet)
- Add a confusion matrix for detailed evaluation
- Export model for deployment
