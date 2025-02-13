<h2>Project Overview</h2>
<p>The MNIST dataset contains grayscale images of handwritten digits, each of size 28x28 pixels. The task is to classify these images into one of 10 categories (digits 0-9).</p>
<p>In this project:</p>
<ul>
    <li>The dataset is normalized and flattened to prepare it for training.</li>
    <li>A DNN with 5 hidden layers, each containing 5 neurons, is used for classification.</li>
    <li>The output layer has 10 neurons with a softmax activation function for multi-class classification.</li>
</ul>

<h2>Features</h2>
<ul>
    <li><b>Data Preprocessing:</b> Normalized image data (values scaled between 0 and 1) and flattened for input.</li>
    <li><b>Deep Neural Network Architecture:</b>
        <ul>
            <li>5 hidden layers with ReLU activation.</li>
            <li>Softmax activation for the output layer.</li>
        </ul>
    </li>
    <li><b>Loss Function:</b> Sparse Categorical Cross-Entropy.</li>
    <li><b>Optimizer:</b> Adam for adaptive learning rate optimization.</li>
    <li><b>Metrics:</b> Accuracy to evaluate model performance.</li>
</ul>

<h2>Prerequisites</h2>
<p>Ensure you have the following installed:</p>
<ul>
    <li>Python 3.7 or higher</li>
    <li>TensorFlow</li>
    <li>NumPy</li>
    <li>Matplotlib</li>
</ul>
<p>To install the required dependencies, run:</p>
<pre>pip install tensorflow numpy matplotlib</pre>

<h2>Dataset</h2>
<p>The MNIST dataset is loaded directly from TensorFlow's <code>keras.datasets</code> module. It consists of:</p>
<ul>
    <li><b>Training Set:</b> 60,000 images</li>
    <li><b>Testing Set:</b> 10,000 images</li>
</ul>

<h2>Model Architecture</h2>
<p>The deep neural network consists of:</p>
<ul>
    <li><b>Input Layer:</b> 784 input features (flattened 28x28 pixel images).</li>
    <li><b>Hidden Layers:</b> 5 layers, each with 5 neurons and ReLU activation.</li>
    <li><b>Output Layer:</b> 10 neurons (one for each digit) with softmax activation.</li>
</ul>

<h2>How to Run</h2>
<ol>
    <li>Clone the repository:
        <pre>git clone https://github.com/your-username/mnist-digit-classification-dnn.git
<h2>Results</h2>
<p>After training the model for 10 epochs, the following results were observed:</p>
<ul>
    <li><b>Training Accuracy:</b> ~97%</li>
    <li><b>Test Accuracy:</b> ~96% (may vary depending on the environment).</li>
</ul>

<h3>Sample Prediction</h3>
<p>For a sample test image, the predicted digit is displayed as:</p>
<pre>Predicted Digit: 2</pre>

<h2>License</h2>
<p>This project is licensed under the MIT License. You are free to use, modify, and distribute this project as per the license terms.</p>

<h2>Acknowledgments</h2>
<ul>
    <li><b>TensorFlow/Keras:</b> for providing an easy-to-use framework for building neural networks.</li>
    <li><b>MNIST Dataset:</b> for the handwritten digit dataset used in this project.</li>
</ul>
