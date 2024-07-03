# Brain_Tumor

This notebook is created with the aim of assisting hospitals create a system in which it can determine whether a patient has a tumor or not, as well as telling us what kind of tumor it is. This notebook creates a neural network which is able to classify brain MRI images which are compromised of glioma, meningioma, pituitary and no tumor. As the data is compromised of different datasets, the images are not all the same shape and size, therefore I had to rectify this to ensure that our model works. I also applied some augmentation to the image to ensure that our model has some variety, which will assist our models learning - hence why my model uses a CNN. I had one model which produced an accurcy of 99% training, 98% validation and 98% testing, which are all accompanied by ~<0.09 loss. The model was able to correctly predit 21 out of 21 images. The model can still be improved by tampering with optimizer and adjusting learning rates, however the results given are satisfactory enough. 


The links and sources for the used data can be found within the notebook itself.
