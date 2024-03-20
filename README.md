The project takes images from a specified input folder, detects faces in them using a pre-trained Haar cascade classifier, and saves the cropped faces into an output folder. It provides parameters such as cascade file, input folder, output folder, rectangle color, rectangle width, scale factor, and number of neighbors to fine-tune the face detection process.

Install OpenCV

``pip install opencv-python``

Obtain the Haar cascade XML file for face detection. You can use the provided faces.xml or download a custom one.

Place the images from which you want to detect faces in a directory named input within the project folder.

Run the script:

``python face_detection.py``

Modify the parameters such as CASCADE, INPUT_FOLDER, OUTPUT_FOLDER, COLOR, WIDTH, SCALE, and NEIGHBORS in the script to customize the face detection process.

The cropped faces will be saved in a directory named output within the project folder.
