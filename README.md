# Handwritten Digit Recognition using CNN (MNIST)

A deep learning project for recognizing handwritten digits using the **MNIST dataset** and a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras**.

This project also includes:

* Data preprocessing
* Data augmentation
* Stress testing the model
* Model evaluation
* Accuracy visualization
* Failure analysis using a confusion matrix

---

## Features

* Trains a CNN on the MNIST handwritten digit dataset
* Uses image augmentation to improve robustness
* Performs stress testing with distorted digit images
* Evaluates model performance on both normal and stressed data
* Visualizes predictions and training accuracy
* Includes failure analysis using confusion matrices

---

## Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Pandas
* Scikit-learn
* Seaborn

---

## Dataset

This project uses the built-in **MNIST dataset** provided by TensorFlow/Keras.

MNIST contains:

* 70,000 grayscale images
* Image size: `28 x 28`
* 10 digit classes (`0–9`)

---

## Model Architecture

The CNN model includes:

* Convolutional Layers
* MaxPooling Layers
* Dense Neural Network Layers
* Dropout for regularization

The model is trained using:

* **Adam Optimizer**
* **Sparse Categorical Crossentropy Loss**

---

## Project Workflow

1. Import required libraries
2. Load MNIST dataset
3. Visualize sample images
4. Preprocess image data
5. Apply data augmentation
6. Build CNN model
7. Train the model
8. Perform stress testing
9. Evaluate performance
10. Visualize results
11. Analyze failures using confusion matrix

---

## Installation

Clone the repository:

```bash
git clone <your-repository-link>
cd <repository-folder>
```

Install dependencies:

```bash
pip install tensorflow numpy matplotlib pandas seaborn scikit-learn
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
Handwriting_MNIST.ipynb
```

Run all cells sequentially.

---

## Results

The model achieves high accuracy on the MNIST test dataset and demonstrates improved robustness through augmentation and stress testing techniques.

The notebook also provides:

* Accuracy/Loss graphs
* Stress test evaluation
* Prediction visualization
* Confusion matrix analysis

---

## Future Improvements

* Deploy as a web application
* Add real-time digit recognition
* Train on custom handwriting datasets
* Experiment with deeper CNN architectures
* Convert model into a mobile-friendly format

---

## Repository Structure

```bash
├── Handwriting_MNIST.ipynb
├── README.md
└── requirements.txt
```

---

## Learning Outcomes

Through this project, I learned:

* Fundamentals of CNNs
* Image preprocessing techniques
* Data augmentation strategies
* Model evaluation methods
* Failure analysis in deep learning

---

## Author

**Mayank Sinha Ray**

Student at Indian Institute of Information Technology Kalyani
Interested in AI, Data Science, and Machine Learning.

---

## License

This project is open-source and available under the MIT License.

