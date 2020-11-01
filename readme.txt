# COVID19 detection from chest X Ray Scans 

The goal of this project is to successfully determine if a patient is COVID19 positive using chest X-ray scans.



The dataset can be found at https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia combined with https://github.com/ieee8023/covid-chestxray-dataset. Decompressing this folder will give you 2 folders by the name of two and all. These are the datasets for the binary problem and multi class problem respectively.

For both the notebooks, we have not commented out the function to train the model. If you decided to train the model yourself, you can do so by directly running the cells where we use the fit_generator() method. If you choose to run the codes with our trained and saved weights, you can do so by loading the model weights as we have mentioned below.


The ipython notebook for the binary task is  is called 'task_1.ipynb'
The weights for the model (Tuned VGG16)  used for evaluating on the test set is in the file "best_model.h5"


The ipython notebook for the multiclass calssification is called 'task_2.ipynb'

In Task 2(Multi label classification) we have used 3 models for evaluating on the test set. 
The file with the weights are as follows:

Tuned VGG16: "best_model_task2.h5"
Tuned Xception: "best_model_2_task2.h5"
Tuned Self created network: "best_model_3_task2.h5"

Model weights can be found here https://drive.google.com/drive/folders/1s0Hpnp5AtsyRyTuuL5hcHFJPGyHRkHzk?usp=sharing
