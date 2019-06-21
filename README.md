# Human-Detection-AAI
Human Detection für the Module AAI 

Benötigte Hardware
1. Raspberry 3 
2. PiCam 
3. Intel Compute Stick

Benötigte Packete 
Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install build-essential cmake unzip pkg-config
 
Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute Stick
$ sudo apt-get install libjpeg-dev libpng-dev libtiff-dev
$ sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
$ sudo apt-get install libxvidcore-dev libx264-dev

Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install libgtk-3-dev

Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install libcanberra-gtk*

Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install libatlas-base-dev gfortran

Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install python3-dev




Befehl zum Ausführuen auf dem Raspberry PI 
1. Terminal öffnen 
2. Ins Verzeichnis gehen in em die Pythondatei liegt. 
3. $ python3 openvino_real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt \--model MobileNetSSD_deploy.caffemodel

Source: https://www.pyimagesearch.com/2019/04/08/openvino-opencv-and-movidius-ncs-on-the-raspberry-pi/
