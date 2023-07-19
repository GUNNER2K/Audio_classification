# Audio-Classification
Audio classification is a subset of machine learning where the classification is done on the audio . This is different from speech recognition . This repo contains the ipynb files , there are two files , One for EDA and the other for processing and Model building . 
A simple ANN model has been implemented . 
just like Text , Machine doesnt understand audio , hence we have to convert these audio waves into meaningful numerical feautres . This is done using Mel-Frequency Cepstral Coefficients(MFCC) , The MFCC summarises the frequency distribution across the window size, so it is possible to analyse both the frequency and time characteristics of the sound. These audio representations will allow us to identify features for classification. 

The library extensively used is the librosa library , which is mainly made for handling audio type data . 
![image](https://github.com/GUNNER2K/Audio_classification/assets/95174361/f192e1cf-a89f-4402-87cd-15f52fd5caae)

the above photo is the representation of waves using the librosa library . 

The dataset is taken from https://urbansounddataset.weebly.com/download-urbansound8k.html 
it contains 8000 samples of various sounds like dog bark , cat meows , car horn , bird chirpings ... etc 
