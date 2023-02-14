<!DOCTYPE html>
<html>
<head>
	<title>Multilabel Classification using VGG16 for COVID, Normal and Pneumonia</title>
</head>
<body>
	<h1>Introduction</h1>
	<p>This project aims to develop a deep learning model for multilabel classification of COVID-19, Normal and Pneumonia cases using VGG16 convolutional neural network.</p>
 <img src="https://storage.googleapis.com/lds-media/images/vgg16-architecture.width-1200.jpg"  width=600, height=150>
 <img src="https://i.stack.imgur.com/108n0.jpg"  width=500, height=250>
<h2>Dataset</h2>
<p>The dataset used for training and testing the model is publicly available on Kaggle. It contains X-ray images of patients with COVID-19, Normal and Pneumonia conditions. The dataset can be downloaded <a href="https://www.kaggle.com/praveengovi/coronahack-chest-xraydataset" target="_blank">here</a>.</p>

<h2>Preprocessing</h2>
<p>The images were preprocessed by resizing them to 256 x 256 pixels, normalizing pixel values and converting them to RGB format. The dataset was then split into training, validation and testing sets.</p>
<img src='https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41598-020-74539-2/MediaObjects/41598_2020_74539_Fig1_HTML.jpg' width=500, height=125>

<h2>Model Architecture</h2>
<p>The VGG16 convolutional neural network was used for the multilabel classification task. The model was pretrained on ImageNet dataset and the last layer was replaced with a dense layer of 3 neurons with sigmoid activation function for multilabel classification. The model was then fine-tuned on the COVID, Normal and Pneumonia dataset.</p>

<h2>Training and Evaluation</h2>
<p>The model was trained for 2 epochs using binary crossentropy loss function and Adam optimizer. The model achieved an accuracy of 91%. </p>

<h2>Conclusion</h2>
<p>The VGG16 model was successful in accurately classifying X-ray images of patients with COVID-19, Normal and Pneumonia conditions. This model can be used as a diagnostic tool for identifying COVID-19 cases in X-ray images.</p>
 <img src='https://journals.plos.org/plosone/article/figure/image?download&size=large&id=10.1371/journal.pone.0265949.g001' width=500, height=350>
</body>
</html>



