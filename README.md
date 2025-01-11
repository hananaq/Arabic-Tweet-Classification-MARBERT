# Arabic-Tweet-Classification-MARBERT
This repository contains a Jupyter Notebook designed for Arabic text classification using the MARBERT model.
MARBERT is a state-of-the-art transformer-based model fine-tuned for tasks involving Arabic natural language processing (NLP).

<h3>Dataset <h3>
the dataset used to train the model can be obtained from the following link https://www.sciencedirect.com/science/article/pii/S2352340923009472#bib0001.
it's collected from Twitter and has two classes Spam and Ham.<br>
I have also added the dataset to this project for ease of use. <br>

<h3>Prerequisites</h3> 
Ensure you have the following dependencies installed before running the notebook:

Python 3.7+ <br>
Jupyter Notebook <br>
Hugging Face Transformers <br>
PyTorch <Br>
scikit-learn <br>
pandas <br>
numpy <br>
matplotlib

<h3>Notes for excution</h3> 
During the execution of this project, the dataset is accessed from Google Drive, and the trained model is saved back to Google Drive. To ensure the project runs correctly, update the path parameter to match your own Google Drive directory.
<br><br>
For example: path = '/content/drive/MyDrive/Colab/AR/'
<br><br>
Replace '/content/drive/MyDrive/Colab/AR/' with the path where your dataset and model will be stored in your Google Drive.
<br>
<br>

<h3>Model Testing</h3>
At the end of training, the classifier is tested by passing two sample tweets:
<ul>
<li>A normal tweet.</li>
<li>A spam tweet.</li>
  </ul>
The trained model successfully predicted the classes of both tweets with an accuracy of 99.9%, demonstrating its effectiveness for Arabic text classification.



