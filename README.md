Download Link: https://assignmentchef.com/product/solved-cse510-project4-anomaly-detection
<br>
In this assignment we will practice to detect anomalies in the benchmark dataset. We will explore deep learning approaches that include building a sequence to sequence MLP and autoencoder.

Dataset

<strong>NAB (Numenta Anomaly Benchmark) </strong>​is a novel benchmark for evaluating algorithms for anomaly detection in streaming, real-time applications. It is composed of over 50 data files designed to provide data for research in streaming anomaly detection. It is comprised of both real-world and artificial timeseries data containing labeled anomalous periods of behavior.

<a href="https://github.com/numenta/NAB/tree/master/data">https://github.com/numenta/NAB/tree/master/data</a>

Tasks

<h3>Part I: MLP for Anomaly Detection</h3>

<ol>

 <li>Choose any dataset from NAB (except those used in class) and prepare it for training (normalize, split between train/test/validation). Explore the dataset by visualizing it and showing statistical parameters about it.</li>

 <li>Build an MLP/LSTM model for predicting a sequence of values (min 5 values). Work with 3 different setups of the window size and the size of the output sequence.</li>

 <li>Using 3 different loss/distance measures identify the anomalies in the dataset.</li>

</ol>

Compare the measurements.

<ol start="4">

 <li>Discuss the results and provide the graphs, e.g. train vs validation accuracy and loss over time. Show a confusion matrix (normal vs anomaly).</li>

</ol>




<h3>Part II: Autoencoder for Anomaly Detection</h3>

<ol>

 <li>Build a Autoencoder model for predicting a sequence of values. Show 3 different Autoencoder setups (e.g. using Dense/LSTM/Conv1D layers).</li>

 <li>For one of the model builded in 1 show the process of hyperparameters tuning (e.g. thresholds, # of layers, activation functions).</li>

 <li>Discuss the results and provide the graphs, e.g. train vs validation accuracy and loss over time. Show the confusion matrix.</li>

</ol>

<strong> </strong>

<h2>Submit the Project</h2>

<ul>

 <li>Submit at <strong>UBLearns &gt; Assignments</strong>​</li>

 <li>The code of your implementations should be written in Python. You can submit multiple files, but they all need to have a clear name</li>

 <li>All project files should be packed in a ZIP file named</li>

</ul>

<strong>TEAMMATE#1_UBIT_TEAMMATE#2_UBIT_project4.zip</strong> (e.g.​       <strong>avereshc_neelamra_project4.zip</strong>).​

<ul>

 <li>Your Jupyter notebook should be saved with the results. If you are submitting python scripts, after extracting the ZIP file and executing command python main.py in the first level directory, all the generated results and plots you used in your report should appear printed out in a clear manner.</li>

 <li>In your report include the answers to questions for each part. You can complete the report in a separate pdf file or in Jupyter notebook along with your code.</li>

 <li>Include all the references that have been used to complete the project.</li>

</ul>

<h2>Important Information</h2>

This project can be done in a team of up to two people. The standing policy of the Department is that all students involved in an academic integrity violation (e.g. plagiarism in any way, shape, or form) will receive an F grade for the course. Refer to the <a href="https://academicintegrity.buffalo.edu/">Academic Integrity websit</a>​ <a href="https://academicintegrity.buffalo.edu/">e</a> <u>​</u>  for more information.