# YOLOv5-models-comparison

Training different YOLOv5 models on 'Face Mask Detection' dataset for comparison. 
[Paper](https://www.researchgate.net/publication/363824867_A_comparative_study_of_YOLOv5_models_performance_for_image_localization_and_classification)


#### Pretrained weights
Pretrained weights for each model can be found in `weights` directory.


#### Scores
Detailed results for each model are located in `results` directory.


#### Jupyter notebook
Jupyter notebook is written with [Google Colab](https://colab.research.google.com/) in mind, but can be used with [Kaggle](https://www.kaggle.com/) for bigger datasets (33h GPU usage time limit). Every Kaggle batch session will end in an irrelevant error caused by differences in working directory structures between Kaggle and Collab. Results still can be downloaded.
Notebook utilizes [ultralytics'](https://github.com/ultralytics/yolov5) YOLOv5 library.

##### Usage
Upload your dataset to [Roboflow](https://roboflow.com/) and export it in YOLOv5 PyTorch format with _show download code_ enabled. Replace `#API#` and `#PROJECTNAME#` and you're ready to go.

#### Dataset
_Face Mask Detection_ dataset used for training is available [here](https://www.kaggle.com/andrewmvd/face-mask-detection). Dataset consists of 1677 images. 

![Prediction example](https://raw.githubusercontent.com/thelcrysis/YOLOv5-models-comparison/main/results/yolov5x/val_batch1_labels.jpg )
