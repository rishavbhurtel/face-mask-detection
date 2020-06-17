# face-mask-detection

dataset link - https://drive.google.com/file/d/1EJ50dPXuESQ5-4q61Hn5IgBfgZE3Bx-I/view?usp=sharing

face mask detector didn't uses any morphed masked images dataset. 
The model is accurate, and since we used the MobileNetV2 architecture, 
it’s also computationally efficient and thus making it easier to deploy 
the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This dataset consists of 3835 images belonging to two classes:

    with_mask: 1916 images
    without_mask: 1919 images

dataset is the collection of:
	Bing Search API
	Kaggle datasets
	RMFD dataset

model gave 93% accuracy for Face Mask Detection after training 

accuracy/loss training curve plot is given in "plot.png" file.

To improve our face mask detection model further, 
we should gather actual images (rather than artificially generated images) of people wearing masks.

we should also gather images of faces that may “confuse” our classifier into thinking
the person is wearing a mask when in fact they are not — potential examples include 
shirts wrapped around faces, bandana over the mouth, etc.




