# Hackathon-Segmentation-with-Sonification-
Image Segmentation with YOLOv3 for identifying objext position and size for creating size dependent pitch sounds.
This project was created as to help blind people visualise the objects around them through sound, we use transfer learning to do object detection then we use the bounding boxes being generated to create or synthesize sound using PyopenAl a pytthon based audio library
the project consists of three major pipelines 1.Object detection 2)using Object detection to get the bounding boxes3)the bounding boxes generated in turn are used to synthesise sounds.

Direction for using python mpd.py file

-> clone the repository 
-> download the yolo-coco model weights and save the folder as yolo-coco in the same repository directory
-> change current working directory as the repository
-> copy the desired video in the video folder as well as output folder
-> run the following command 
   python3 mod.py -i video/filename.avi -p output/filename.py -y yolo-coco
