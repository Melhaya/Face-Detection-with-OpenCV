# Face-Detection-with-OpenCV

Using OpenCV to detect faces from images.

OpenCV’s deep learning face detector is based on the Single Shot Detector (SSD) framework with a ResNet base network. 

To star the code, Write this command in the promt: 
python detect_faces.py --image path/of/images_folder --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

* The .prototxt file which define the model architecture (i.e., the layers themselves)
* The .caffemodel file which contains the weights for the actual layers
