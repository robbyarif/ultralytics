# YOLO Exploration

Exploration notebooks and scripts to run YOLO11 and YOLO12

## How to run

- Create virtual environment
- Install ultralytics
- Download dataset from COCO
- Run notebook.

## CLI

We also can use YOLO CLI to manage all the process from downloading dataset to train.

For example to train a segmentation model using YOLO12 segmentation model from scratch we can run
 
`yolo segment train data=coco.yaml model=yolo12n-seg.yaml epochs=10 imgsz=640`