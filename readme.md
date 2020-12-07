
# Chest X-Ray classification for COVID19 detection

 ![](https://img.shields.io/badge/python-3.7.6-green.svg?style=flat) ![](https://img.shields.io/badge/tensorflow-2.3.0-red.svg?style=flat) ![](https://img.shields.io/badge/keras-2.4.3-orange.svg?style=flat)

# Objective

The goal of this project is to determine COVID19 from chest X-ray scans. Project is divided into two sub part:
* **Binary Classification** : Classification of chest X-Ray scans between COVID19 patient and NORMAL person.
* **Multi-class Classification** : Classification of chest X-Ray scans among COVID19 patients, Bacterial Pneumonia patients and Viral Pneumonia patients and NORMAL person.

# Dataset
Model is trained and evaluated on publicly available [dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) released by the University of Montreal. Decompressing this folder will give you 2 folders by the name of two and all. These are the datasets for the binary problem and multi class problem respectively. Dataset contain one folder each for binary classification(130 X-rays) and multiclass classification 270 X-rays) respectively.

# Code

**Binary Classification:** Inside Binary Classification folder Binary Classification.ipynb contains the code for this part. The weights for the model (Tuned VGG16) used for evaluating on the test set is in the file "best_model.h5"

For both the notebooks, I have not commented out the function to train the model. If you decided to train the model yourself, you can do so by directly running the cells where we use the fit_generator() method. If you choose to run the codes with our trained and saved weights, you can do so by loading the model weights as we have mentioned below.


**Multiclass Classification:** Inside Multiclass Classification folder Multiclass Classification.ipynb contains the code for this part. 3 models were used to evaluate the test set. The file with the weights for 3 models:

* Tuned VGG16: "best_model_task2.h5"
* Tuned Xception: "best_model_2_task2.h5"
* Tuned Self created network: "best_model_3_task2.h5"

All model weights can be found [here](https://drive.google.com/drive/folders/1s0Hpnp5AtsyRyTuuL5hcHFJPGyHRkHzk?usp=sharing)

# Report: 

For detail understanding refer [documentation](Final_Report.pdf)
