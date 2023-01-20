# YOLOv5 Real-Time Object Detection for CCTV
### Introduction
#### The YOLO (You Only Look Once) series of object detection models are known for their real-time performance and accuracy. In this project, we will be using YOLOv5 to detect guns and knives in CCTV footage in real-time. This project is a proof-of-concept for using YOLOv5 in a security setting to improve public safety.

### Requirements
    NVIDIA GPU
    CUDA and cuDNN (version 10.2)
    Python 3.8 or later
    OpenCV
    PyTorch
    YOLOv5
    A dataset of CCTV footage containing guns and knives
    Installation
    Install CUDA and cuDNN. You can find the installation instructions on the NVIDIA website.

### Clone this repository.

##### Copy code
     > git clone https://github.com/AlexeyAB/darknet
#### Install the required Python packages by running the following command in the project directory:
##### Copy code
     > pip install -r requirements.txt
#### Download the pre-trained YOLOv5 weights from the official YOLO website.
##### Copy code
     > https://github.com/AlexeyAB/darknet
    
#### Build the darknet library.
##### Copy code 
     > cd darknet
     > make
### Usage

- Collect CCTV footage containing guns and knives.

- Run the object detection script on the CCTV footage.

##### Copy code
     > python detect.py --input path/to/video.mp4 --output path/to/output.avi --weights path/to/weights.pt

<pr> The script will detect guns and knives in the footage and save the output to the specified location.
</pr>

## Conclusion
#### In this project, we have shown how YOLOv5 can be used for real-time object detection in CCTV footage to detect guns and knives. This proof-of-concept demonstrates the potential for using YOLOv5 in a security setting to improve public safety. However, it is important to note that this project is for educational purposes only and should not be used in a real-world setting without proper testing and evaluation.