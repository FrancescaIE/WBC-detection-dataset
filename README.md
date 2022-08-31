# Dataset for Detection of White Blood Cells of the Juvenile Visayan Warty Pig in Blood Smear Images

This dataset was prepared in part of a study employing [YOLOv5](https://github.com/ultralytics/yolov5/) for white blood cell image detection and counting of juvenile Visayan Warty pigs. The dataset is 
important in supplying material for exploring the application of machine learning for veterinary use. There are a total of **665** annotated 416 x 416 JPG files and their corresponding YOLO Darknet TXT files. 
The images have been split into training, validation, and testing folders with a 70:15:15 ratio.

----

### Folder structure:
1. **“test”** folder contains two subfolders:
      - "images" containing the 98 annotated images
      - "labels" containing 98 TXT files
2. **"train”** folder contains two subfolders:
      - "images" containing the 459 annotated images 
      - "labels" containing the 459 TXT files
3. **“valid”** folder contains two subfolders:
      - "images" containing the 98 annotated images
      - "labels" containing 98 TXT files

----

### Methodological information:
#### *Date of data collection*
June 2021 to November 2021

#### *Sample Collection*
Data was collected at Bacolod City, Negros Occidental, Philippines. 
A smartphone was used to capture images of the peripheral thin blood smears of juvenile Visayan warty pigs viewed under a Olympus® CX23 compound microscope 
set at 100x Oil Immersion.

#### *Methods for processing the data:* 
The images were manually annotated using [LabelImg](https://github.com/heartexlabs/labelImg/).
