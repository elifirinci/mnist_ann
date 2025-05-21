## 🧠 MNIST Digit Classification with Artificial Neural Network

This project demonstrates how to build, train, and evaluate an **Artificial Neural Network (ANN)** for handwritten digit classification using the **MNIST dataset**. It is implemented in Python with **TensorFlow/Keras**.

### 📁 Project Structure

* `Mnist.ipynb`: Main Jupyter Notebook that includes:

  * Data loading and visualization
  * ANN model building and training
  * Accuracy and loss plots
  * Sample predictions and performance evaluation

### 🔧 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* scikit-learn

### 📊 Dataset

* **MNIST Dataset**: A classic benchmark in machine learning, consisting of 60,000 training and 10,000 test grayscale images of handwritten digits (0–9), each 28x28 pixels.

### 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mnist-ann.git
   cd mnist-ann
   ```

2. Install the requirements:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Mnist.ipynb
   ```

### 🧪 Model Summary

* **Input Layer**: 784 neurons (flattened 28x28 images)
* **Hidden Layers**: Dense layers with ReLU activation
* **Output Layer**: 10 neurons with softmax (for 10 classes)

### 📈 Results

The trained model achieves high accuracy on the test set, with clear visualizations of predictions and misclassified digits.

### 📝 License

This project is open source and available under the [MIT License](LICENSE).


