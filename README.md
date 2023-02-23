# StackGAN - Synthesizing high-quality images from text descriptions

Implementation

Implementation of StackGAN are in two Stages:

Stage - 1: Train the text input along with random noise to a low resolution image of 64x64x3
Stage - 2: Train the low resolution image to high resolution image 256x256x3

Create 3 folders (test, weights,results_stage2) in your current working directory.

1. weights (your model weights will be saved here)
2. Test (generated images from our stage I StackGAN)
3. results_stage2 will have the generated images from stage2 fo StackGAN

About Dataset                                                                                      

Dataset Name: Caltech-UCSD Birds-200-2011
Download from : http://www.vision.caltech.edu/visipedia/CUB-200-2011.html

Text Embedding Model
Download char-CNN-RNN text embeddings for birds from :

https://drive.google.com/file/d/0B3y_msrWZaXLT1BZdVdycDY5TEE/view?resourcekey=0-sZrhftoEfdvHq6MweAeCjA or https://github.com/hanzhanggit/StackGAN

char-CNN-RNN-embeddings.pickle — Dataframe for the pre-trained embeddings of the text.
filenames.pickle — Dataframe containing the filenames of the images.
class_info.pickle — Dataframe containing the info of classes for each image.
