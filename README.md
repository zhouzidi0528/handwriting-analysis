# handwriting-analysis
1 crop(1).ipynb   Image extraction script  It can be run by editing the picture name at the end.

2 final 1.ipynb    Combining extraction and recognition  It can be run by editing the picture name at the end.

3 make_tfrecords.ipynb  Convert images to tfrecords files, tensorflow specifies the data file format

4 train.ipynb  modeling training script

5 make_pb.ipynb  Generate a Pb file from the trained model

6 frozen_model2.pb  It is the trained model which can be called directly

7  prediction测试集.ipynb  This script can be used to recognize single or multiple pictures. It can also test the accuracy on the test set, it can be run by setting the path of the folder which stores the images 
