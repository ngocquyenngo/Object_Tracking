
1. Object tracking using YOLO and a tracker(KCF, MOSSE, CSRT) in openCV 

   File YOLOv3 weight can be downloaded from link https://pjreddie.com/media/files/yolov3.weights

   Comparison of KCF, MOSSE and CSRT tracker in openCV:

   - Use CSRT when you need higher object tracking accuracy and can tolerate slower FPS throughput

   - Use KCF when you need faster FPS throughput but can handle slightly lower object tracking accuracy

   - Use MOSSE when you need pure speed

2. Visual tracking using Multi-domain convolutional neural network (MDNet) source code https://github.com/HyeonseobNam/py-MDNet with a few modifications. 

   Link of modified file: https://drive.google.com/drive/folders/1qvDSG4CmUBDY9wJUXieesYbtaO0HfjG1?usp=sharing
