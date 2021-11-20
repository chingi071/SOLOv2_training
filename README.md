# SOLOv2_training
Use solov2 training instance segmentation, the training set data is downloaded from [roboflow Raccoon Dataset](https://public.roboflow.com/object-detection/raccoon) and then labeled.

The labeled data is placed in the raccoon_dataset folder.

## Create dataset
Before training, first convert the training data into COCO format. 

Execute create_dataset.ipynb to convert the training data format.

## Training
Execute training.ipynb for training. 

## Predict result
The predicted results are as follows
![image](https://github.com/chingi071/SOLOv2_training/blob/main/demo_out.jpg)

## Flow
The detailed process can refer to my Medium: [SOLOv2 訓練教學](https://medium.com/ching-i/solov2-%E8%A8%93%E7%B7%B4%E6%95%99%E5%AD%B8-90591960b5c7)
