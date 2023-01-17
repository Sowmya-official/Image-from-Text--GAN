# StackGAN - Synthesizing high-quality images from text descriptions

Implementation of "Stage 1 " of StackGAN 

Stage I of StackGAN  
1- takes input as text,  
2- convert the text to embedding using our pre-trained character level embedding.  
3- Then, we give this embedding to Conditional Augmentation (CA) and  
4- then to Stage I Generator which gives us low-resolution 64*64 images. 
