# LALakersAI
An iOS app that uses a CoreML model to take informations about Los Angeles Lakers' players.

## CoreML Model
The model used by the app is YOLOv3 trained using 2230 images (1775 train and 445 test) of Los Angeles Lakers' highlights.

## Citations
Model: [YOLOv3](https://pjreddie.com/darknet/yolo/)

Similar app used to develop this application: [YOLOv3-CoreML](https://github.com/Ma-Dan/YOLOv3-CoreML)

## Useful Google Colab file

[From YOLOv3 to Custom Object Detection](https://colab.research.google.com/drive/1BNajhZAxU_8J8DoK43y2JEJog0l4Hb6X)

## Before Building the App
Unzip the first element contained in zippedModel folder and copy the unzipped .mlmodel file into LALakersAI/Utils/
