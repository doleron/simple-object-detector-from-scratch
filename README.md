# simple-object-detector-from-scratch

This repository has educational purposes only. It is shown how to build a simple Object Detector from scratch using Tensorflow &amp; Keras.

The code to build the detector is shown in this [notebook](simple_obj_detector.ipynb)

You can also run the code on this [colab notebook](https://colab.research.google.com/drive/1P1CC2f-V_oBTUJFwblgmW-E9xe-19Osi).

Check this story on medium for more details: https://medium.com/@doleron/building-your-own-object-detector-from-scratch-bfeadfaddad8

![model predictions](https://raw.githubusercontent.com/doleron/simple-object-detector-from-scratch/main/test_od.png)

## Notes

The model is trained using the Labeled Mask database: https://www.kaggle.com/datasets/techzizou/labeled-mask-dataset-yolo-darknet

This repo uses IoU (Intersection over Union) to check the model performance on test data. The original implementation of IoU was get from Pyimagesearch: https://pyimagesearch.com/2016/11/07/intersection-over-union-iou-for-object-detection/

![model diagram](https://raw.githubusercontent.com/doleron/simple-object-detector-from-scratch/main/model.png)

This repository was tested locally on Ubuntu 22.04 and also on Google Colab: https://colab.research.google.com/drive/1P1CC2f-V_oBTUJFwblgmW-E9xe-19Osi


