Digit Recognition - Kaggle Competition
------------------------------------------
* The objectif of this competition is the best predictif model for `image recognition`. For more details about the dataset, feel free to visit `Kaggle website` [here](https://www.kaggle.com/c/digit-recognizer/data)

* Rank : `649/3282 - Top 20% `




Files 
------------------------------------------

* `Digit_recognition.ipynb` : Jupyter notebook containing the code used.
* `train.csv / test.csv` : the data used to train our deep convolutional neural network.


Frameworks
------------------------------------------

* Many frameworks are required:
	* `Tensorflow`
	* `Keras API` - Tensorflow Backend
	* `Pandas library`
	* `numpy library`


Deep Neural Network for image recognition
------------------------------------------

* My model is inspired from `Lenet-5` deep convolutional neural network but with :
	* More `Layers`
	* More `Units in the dense layer`
	* Different `filters`

* To reduce overfitting, we implemented two technics :
	* `Dropout`
	* `Data augmentation`

* The model is trained on almost 250 epochs ( ~45 min with `GPU` )


Results
------------------------------------------

* We got a model with `Training accuracy = 0.9980` and `Validation accuracy = 0.9933`, which implies a model with : 
	* `Low bias` i.e without underfitting
	* `Low variance` i.e without overfitting



