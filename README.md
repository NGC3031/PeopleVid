# PeopleVid
Ripped from the net https://data-flair.training/blogs/ with some minor mods and bug fixes, image recognition in python.
Requirements pip/3 install opencv-python pip/3 install imutils pip/3 install numpy

USAGE:
Video file as input:
python main.py -v ‘Path_to_video’

Image file as input:
python main.py -i ‘Path_to-image’

Camera input:
python main.py -c True

Save the output:
Python main.py -c True -o ‘file_name’

COMMENTS:
cv2 does the work, imutils - image processing, numpy for drawing. Gradient Histogram approach, so a basic model.
Still useful as a starting point and was really just a proof of concept. Hacked and borrowed from the net. 
