## Vinbigdata Full Pipeline
* Yolov5 
* MMDETECTION - VFNet
* DETECTRON2 - Faster RCNN
* Two Classifier for Abnormal vs Normal - EFFICIENTNETB5
* (CV 0.994) 15 Classifier for an individual class - 512 size EFFICIENTNETB5 + 512 size DenseNet201 + 768 size EFFICIENTNETB5
## Common things

1. Data Preparation -> 2. Preprocessing -> 3. Model train -> 4. Model inference(with Two classifier or 15 classifier) 
-> 5. CV Checking ->6. Model Ensemble

#### Only Google Colab is supported.
