# yolov3-spp-tiny
Lighter version of yolov3-spp with some new enhancement.

#### credit to https://github.com/ultralytics/yolov3
#### weights https://drive.google.com/drive/folders/1dKsI2XFQZ-pNX8f4-gMmxWiIkJnk-yQL?usp=sharing
#### Directory Distribution: https://github.com/rayjan0114/YOLO_IEEE

# Training

**Start Training:** `python3 train.py`.

**Resume Training:** `python3 train.py --resume` to resume training from `weights/latest.pt`.

# New Enhancement
Comparing to the origin repo from Glenn Jocher's, we do (1).class-wise kmeans (2).tanh shape for tuning hyperarameter iou_t
(3).cutout data augmentation (4).yolov3-spp-tiny model structure.

#### This is an repo working on a competition, so more details will be released after the competition finished.

