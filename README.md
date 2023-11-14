# See in the Dark using CNN

* Imaging in low light is very challenging due to low photon count and the presence of noise. High ISO can be used to increase brightness, however, it also amplifies noise. Postprocessing, such as scaling or histogram stretching can be applied, but this does not resolve the low signal-to-noise ratio (SNR) due to low photon counts. Short-exposure images suffer from noise, while long exposure can induce blur and is often impractical.

* To support the development of learning-based pipelines for low-light image processing, we are working on the See-in-the-Dark (SID) dataset, which contains raw short-exposure low-light images, with corresponding long-exposure reference images. Using the presented dataset, we develop a pipeline for processing low-light images, based on end-to-end training of a fully-convolutional network. The network operates directly on raw sensor data and replaces much of the traditional image processing pipeline, which tends to perform poorly on such data.

* We have two approaches to address the issues:
  
  1. Traditional Image Processing approach
  2. Deep Learning based Fully Connected CNN based approach with U-Net architecture
 
There are two different **Colab Notebooks** for the above approaches.

* You can download the SID Dataset from [here](https://storage.googleapis.com/isl-datasets/SID/Sony.zip).
