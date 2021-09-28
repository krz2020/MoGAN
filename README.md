# Documentation for Training Multi-Objective Generative Adversarial Network for 3D Chair Dataset

**requirements.txt**

> A text file produced by pip describing the necessary python libs to reproduce the same virtual environment that is used for training. 
> ```shell
> pip freeze > requirements.txt  # The requirements file can be created by calling this command
> pip install -r requirements.txt  # The packages specified in the requirements file can be installed by pip by calling this command
> ```

**MoGAN_Chair.ipynb**

> * The most essential notebook for this project.
> * It contains code to automatically download the necessary dataset, and pretrained auxiliary discriminator models
> * See the notebook


**Auxiliary_Discriminators_Chair.ipynb** 

> * In case one might want to train their own auxiliary discriminators models instead of using pretrained models by researchers. 
> * See the notebook


**Utils.ipynb** 

> * Include some utility functions such as creating gifs from trained samples and finding most similar geometries from dataset. 
> * See the notebook