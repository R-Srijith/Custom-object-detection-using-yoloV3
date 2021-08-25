# Custom-object-detection-using-yoloV3

* This is a custom object detection project that uses yoloV3. 
* The model detects three classes 'mask_weared_incorrect','with_mask'and 'without_mask'.
* The dataset used for training is the Face Mask detection dataset form kaggel. Link: https://www.kaggle.com/andrewmvd/face-mask-detection

# Methadology

* convert the xml annotations in the dataset to yolo format using Convert_VOC_to_yolotxt.py
* upload the dataset to your google drive account to use google colab for training.
* mount your drive in the colab notebook and clone darknet repo from  'https://github.com/AlexeyAB/darknet.git'
* Apply neccessary changes to the configuration file and train your model
* You can now use the new weights to perform object dection
* To perform real time object dection using webcam refer to Real_time_object_detection_using_web_cam
* To perform object dection on images refer to image_testing
* You can see some sample outputs of the model at Sample_outputs


