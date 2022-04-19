# faceMask_detector
we have 2 main files

training.py -> for loading the model and adding more layers to it and training it for a spefic dataset

datect_mask.py -> for loading thje trained model and to activate the video stream to detect face 


how to run:
1) check if the camera connected to the raspberry  pi by running respistill -o test.jpg
2) cd faceMask_detector
3) python3 detect_mask.py
