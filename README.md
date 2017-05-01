# UGP

#My project's README

How to run the files :-

1) Install opencv

2) Save files in the directory "/opencv/samples/python/" Or Instead of step 2 paste this file in the same directory as (facedetect.py) //your opencv will have a facedetect.py

3) Install openface from github

4) In the directory "openface/demos/" save the files compare0.py and cluster0.py //in this dir you already have the file compare.py

A. facedet.py takes sample video and extract all the faces appearing in the video saves them in the specified folder

B. compare0.py takes as input the face dir created by facedet.py and saves a matrix N x 128 where N is no. of images.

C. cluster0.py takes as input the matrix and clusters it. // look for comments in the code for the details

