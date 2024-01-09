# Pashto-Text-Graphic
Pashto Text &amp; Graphics 
Layout analysis is the main component of a typical Document Image Analysis (DIA) system and performs an important role in pre-processing. However, regarding the Pashto language, the document images are not explored so far. Therefore, here is a notable contribution regarding the creation of a real dataset. The dataset contains more than 1,000 images of the Pashto documents captured by a camera. The dataset we applied the Convolution Neural Network (CNN) following a deep learning technique. Our intended method is based on the development of the advanced and classical variant of Faster R-CNN called Single-Shot Detector (SSD). The evaluation was done by examining the 300 images from the test set. In this way, We achieved a mean average precision (mAP) of 84.90%
# Guide to use the code and data

The main repository contains three folders:
Data
Pipeline
Checkpoint
The data folder contains the tf record files (already created), if one wants to create such files, he/ she can use ”generate_tfrecord.py” script. The rest of the code can be found in “TextVsGraphicsPashto.ipynb”.
Make sure that the path to checkpoints and tefrecord files is correctly mentioned in the config file located in the “pipeline” folder.

Note:  The experiment was carried out on Google Colab, therefore, we recommend using the Google Colab, as the using of “TextVsGraphicsPashto.ipynb” file will be more convenient .
