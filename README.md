# Image-Caption-Generator
IMPORTANT LINKS:

Dataset link: https://www.kaggle.com/shadabhussain/flickr8k

VGG-16 predefined weights: https://github.com/fchollet/deep-learning-models/releases/download/v0.1/vgg16_weights_tf_dim_ordering_tf_kernels.h5


HOW TO EXECUTE THE CODE:

1. Make a new directory and download the image-caption-generator.ipynb file in the directory.

2. From the Dataset Link (https://www.kaggle.com/shadabhussain/flickr8k) download the
complete dataset and save it in your directory.

3. Open the image-caption-generator.ipynb file in Jupyter Notebook.

4. In the 2nd code cell give the path to your "Flicker8k_Dataset" folder for the "dir_Flickr_jpg" variable.
And the path for the "Flickr8k.token.txt" file for the "dir_Flickr_text" variable.

5. From the link (https://github.com/fchollet/deep-learning-models/releases/download/v0.1/vgg16_weights_tf_dim_ordering_tf_kernels.h5)
Download the VGG-16 Model pre-defined weights for image classification and save it in your directory.

6. In the 12th code cell give the path to your downloaded predefined weights (.h5 file) in the previous step.

7. Run all the cells.

8. After execution of all the cells is complete (it will take 2-3 hours), the last cell will open a GUI interface.

9. Click on the "Choose Image" button in GUI and upload an image from dataset or any image from google
and then click on the "Classify Image" button to get the predicted caption from the model.
