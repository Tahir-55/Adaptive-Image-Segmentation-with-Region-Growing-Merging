Region Growing and Merging for Image Segmentation

This project develops picture segmentation approaches using the Region Growing and Region Merging algorithms. These methods allow the identification of regions based on similarity in a picture by starting at a seed point (Region Growing) and merging nearby areas that meet a criterion for similarity (Region merging).

Features "Region growing" is a seed-based technique that increases areas by incorporating neighboring pixels that satisfy a threshold. Region Merging: A method for segmenting color and grayscale images that enhances segmentation results by joining previously segmented regions based on pixel similarity. Dynamic testing is made possible via a configurable threshold and random seed generation. Interpolation techniques like ARBH and Laplacian, together with enhancement functions like brightness and contrast modulation, are used for pre-processing images. Image processing: This method efficiently use algorithms to demonstrate segmentation by converting images into grayscale.

Dependencies Python 3.x OpenCV Numpy Matplotlib opencv-python skimage scipy Skimage (for region merging) Google Colab (for file uploads if using Colab)
