# FINGERPRINT CLASSIFICATION USING MOCOV2-RESNET

This contains the following folders:
1)  Augmented Images :- This contains 200 folders. Each folder contains the augmented images of the finger prints available of each person. i.e the 4 finger prints available per person and each finger print has 4 augmentations resulting into 16 images per person after augmentation. This folder was used just for testing purposes.
2) Denoise Images:- This folder contains all the denoised images of all the images given.
3) Final images:- This is a subset of augmented images which we used for testing each time.
4) Models :- Empty folder
5) Raw Images :- This contains the given biometric dataset 'IITB Fingerprint' which has been organised.
6) Results Folder :- Images of the final plots which were tried by us.
7) Final_code.ipynb :- Useless
8) Group_augmented.py, grouping_images.py :- Code used for grouping into single folders(used just for convinence)
9) Resnet.py :- It has the final resnet block which uses the pretrained weights given by mocov
10) Script.py :- used for denoising and augmentation folders.
11) train_mocov.py:- used for training of mocov and getting the weights