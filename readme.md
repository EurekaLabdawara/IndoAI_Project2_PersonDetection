# About Project
This is a computer vision project with the task to detect and track person in image or video.
The objective of this project is to:
1. Exploring different architectural of neural network such as Yolo V8 and Faster RCNN. Metric to compare:
- Inference Time
- Training Time
- Accuracy
2. Try to re-train or finetuning the models with or without existing pretrained model/weight.
3. Implement simple inference with different inputs:
- Image (Link, Upload)
- Static / File Video (Link, Upload)
- Video Stream (Live Webcam) 

# Project Structure

```
.
├─Notebooks                                     #Txt File for Label
├──Person_Tracking_Inference.ipynb              #Notebook for inference in GCollab/Cloud Platform
├──project-2-faster_RCNN.ipynb                  #Notebook for re-train/finetune Faster RCNN
├──Retrain YoloV8m no pretrain.zip              #project for re-train without pretrained weight
├──Retrain YoloV8m with pretrain.zip            #project for re-train with pretrained weight
├──Testing Pretrain YOLOv8m No Train.ipynb      #Validation and testing for without pretrained
├──Testing Pretrain YOLOv8m with Train.ipynb    #Validation and testing for with pretrain
├─YoloV8_Inference_local                        #Yolo local inference project 
├──models                                       #yolo model used for inference
├──predict.py                                   #Python script for local live webcam inference
├──requirements.txt                             #optional to use, dependencies for local inference  
├─Project 2-Person Detection_Presentation.pptx  #Presentation file
```