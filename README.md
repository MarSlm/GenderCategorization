Gender Categorization

Gender Categorization is a real-world dataset containing images of men and women. This repository contains the source code needed to built machine learning algorithms that can "recognize" the gender of people in the images.

For this purpose, we use deep learning and neural network techniques through Tensorflow.

The dataset can be downloaded from here: https://www.crowdflower.com/data-for-everyone/ . In order to download the images we use code in file 'Data_Download.py'. Images are downloaded as grayscale images in numpy.array format.  

In the 'input_data' folder there are infromation about the data that we used as input in the models. In file 'y.txt' there are the classes of the download images. In file readme.txt there is a URL which leads to the downloaded images. The images should be download as 'test.txt'. The two files should be downloaded and placed in a folder. The path of the files should be used in the code.

In 'Codes' file there are codes while in 'FilesMayNeed' necessary files (texts files) for running the codes are included. More specifically the last file includes the following: pred.txt, real.txt are used for keeping what classes are predicted and what are the real classes of the data, respectively img.txt is used as input to showImage.py in order to show/save a sample of the dataset.

File 'report' contains a short report for our work on the project while 'presentation' file contains our final presentation.

This project was conducted as part of the "Social Media Analytics" class of the M.Sc. in Business Analytics, Athens University of Economics & Business.

The project implemented by the following members :  
Alexandra Gkiali,  
Athanasios Gkinakos,  
Paraskevi Koutsioumpa,  
Konstantina Malliari,  
Maria Salemi
