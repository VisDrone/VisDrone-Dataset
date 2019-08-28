# VisDrone-Dataset

Drones, or general UAVs, equipped with cameras have been fast deployed to a wide range of applications, including agricultural, aerial photography, fast delivery, and surveillance. Consequently, automatic understanding of visual data collected from these platforms become highly demanding, which brings computer vision to drones more and more closely. We are excited to present a large-scale benchmark with carefully annotated ground-truth for various important computer vision tasks, named VisDrone, to make vision meet drones. The VisDrone2019 dataset is collected by the AISKYEYE team at Lab of Machine Learning and Data Mining , Tianjin University, China. The benchmark dataset consists of 288 video clips formed by 261,908 frames and 10,209 static images, captured by various drone-mounted cameras, covering a wide range of aspects including location (taken from 14 different cities separated by thousands of kilometers in China), environment (urban and country), objects (pedestrian, vehicles, bicycles, etc.), and density (sparse and crowded scenes). Note that, the dataset was collected using various drone platforms (i.e., drones with different models), in different scenarios, and under various weather and lighting conditions. These frames are manually annotated with more than 2.6 million bounding boxes of targets of frequent interests, such as pedestrians, cars, bicycles, and tricycles. Some important attributes including scene visibility, object class and occlusion, are also provided for better data utilization.

The challenge mainly focuses on four tasks: 

(1) Task 1: object detection in images challenge. The task aims to detect objects of predefined categories (e.g., cars and pedestrians) from individual images taken from drones. 

(2) Task 2: object detection in videos challenge. The task is similar to Task 1, except that objects are required to be detected from videos.

(3) Task 3: single-object tracking challenge. The task aims to estimate the state of a target, indicated in the first frame, in the subsequent video frames.

(4) Task 4: multi-object tracking challenge. The task aims to recover the trajectories of objects in each video frame.


## Download

### Task 1: Object Detection in Images 

VisDrone2019-DET dataset

    trainset (1.44 GB): [BaiduYun](https://pan.baidu.com/s/1rHwQKNsgVnqddUxxZwPk2g)| GoogleDrive
    
    valset (0.07 GB):  BaiduYun | GoogleDrive
    
    testset-dev (- GB):   BaiduYun | GoogleDrive
    
    testset-challenge (0.28 GB): BaiduYun | GoogleDrive
    
VisDrone2019-DET toolkit: 

    Matlab beta

### Task 2: Object Detection in Videos

VisDrone2019-VID dataset

    trainset (7.53 GB):  BaiduYun | GoogleDrive
    
    valset (1.48 GB):  BaiduYun | GoogleDrive
    
    testset-dev (- GB):  BaiduYun | GoogleDrive
    
    testset-challenge (2.70 GB):  BaiduYun | GoogleDrive 
    
VisDrone2019-VID toolkit: 

    Matlab beta

### Task 3: Single-Object Tracking 

VisDrone2019-SOT dataset

    trainset_part1 (7.78 GB):   BaiduYun | GoogleDrive
    
    trainset_part2 (12.59 GB):  BaiduYun | GoogleDrive
    
    valset (1.29 GB):   BaiduYun | GoogleDrive
    
    testset-dev (- GB):  BaiduYun | GoogleDrive
    
    testset-challenge_part1 (17.40 GB):  BaiduYun(Password:e4xz) | GoogleDrive
    
    testset-challenge_part2 (17.31 GB):  BaiduYun(Password:91p4) | GoogleDrive
    
    testset-challenge_initialization:  BaiduYun(Password:xfs4) | GoogleDrive
    
VisDrone2019-SOT toolkit: 

    Matlab beta
    
### Task 4: Multi-Object Tracking 

VisDrone2019-MOT dataset

    trainset (7.53 GB):  BaiduYun | GoogleDrive
    
    valset (1.48 GB):  BaiduYun | GoogleDrive
    
    testset-dev (- GB):  BaiduYun | GoogleDrive
    
    testset-challenge (2.70 GB):  BaiduYun | GoogleDrive
    
VisDrone2019-MOT toolkit:

    Matlab beta


## Citation 

@article{zhu2018vision,

  title={Vision meets drones: A challenge},
  
  author={Zhu, Pengfei and Wen, Longyin and Bian, Xiao and Ling, Haibin and Hu, Qinghua},
  
  journal={arXiv preprint arXiv:1804.07437},
  
  year={2018}
}


