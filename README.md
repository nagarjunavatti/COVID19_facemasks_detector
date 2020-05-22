# COVID19_facemask_detector
COVID19_facemask_detector is a computer vision based project. COVID19_facemask_detector is developed using OpenCV, Keras/TensorFlow, and Deep Learning. COVID19_hawk_eye basically detects whether the person is wearing a facemask or not and accordingly decides whether to allow the person to pass or not 

detect_mask_image.py and detect_mask_video.py run using command line arguments

detect_mask_image.py -> performs face mask detection in static images
detect_mask_video.py -> using your webcam, this script applies face mask detection to every frame in the stream

COMMAND LINE ARGUMENTS FOR CODES:

detect_mask_image.py : python detect_mask_image.py --image examples/example_01.png (you can parse any image from your local drive)

detect_mask_video.py : python detect_mask_video.py

