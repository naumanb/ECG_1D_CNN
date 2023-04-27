<h1>Arrhythmia Classification using 1D CNN</h1>
<p>This project uses a 1D Convolutional Neural Network (CNN) to classify arrhythmias in ECG data. The dataset used is the MIT-BIH Arrhythmia Database, which contains ECG recordings of various arrhythmia types. The project is implemented using TensorFlow, Keras, and other Python libraries.</p>

<h2>Table of Contents</h2>
<ol>
  <li>Requirements</li>
  <li>Dataset</li>
  <li>Usage</li>
  <li>Project Structure</li>
  <li>License</li>
</ol>

<h2>Requirements</h2>
<p>To install the required Python packages, run the following command:</p>

<pre><code>pip install biosppy tensorflow keras sklearn matplotlib numpy scipy pywt pandas
</code></pre>

<h2>Dataset</h2>
<p>The dataset can be downloaded from the MIT-BIH Arrhythmia Database. To download the dataset, navigate to the link and download the files in the "mitdb" folder. Save the files in a directory of your choice (e.g., "mitDB").</p>

<h2>Usage</h2>
<ol>
  <li>Download the dataset and save it in a directory.</li>
  <li>Update the path variable in the Jupyter Notebook file with the directory where the dataset is saved.</li>
  <li>Run the Jupyter Notebook cells to preprocess the data, train the 1D CNN model, and evaluate the model's performance.</li>
</ol>

<pre><code>path = "your_directory_path_here/mitDB/"
</code></pre>

<h2>Project Structure</h2>
<p>The Jupyter Notebook consists of the following sections:</p>
<ul>
  <li>Importing required libraries</li>
  <li>Defining plot settings and functions</li>
  <li>Reading and processing the dataset</li>
  <li>Data preprocessing</li>
  <li>Training and testing the 1D CNN model</li>
  <li>Model evaluation and confusion matrix</li>
</ul>
<p>By following the steps mentioned in the "Usage" section, you can train and evaluate the 1D CNN model for arrhythmia classification using the MIT-BIH Arrhythmia Database.</p>

<h2>License</h2>
<p>This project is licensed under the MIT License. See the LICENSE file for details.</p>
