# VisDrone-Dataset

![VisDrone](http://aiskyeye.com/upfile/1524040398110image_sample.jpg)

Drones, or general UAVs, equipped with cameras have been fast deployed to a wide range of applications, including agricultural, aerial photography, fast delivery, and surveillance. Consequently, automatic understanding of visual data collected from these platforms become highly demanding, which brings computer vision to drones more and more closely. We are excited to present a large-scale benchmark with carefully annotated ground-truth for various important computer vision tasks, named VisDrone, to make vision meet drones. The VisDrone2019 dataset is collected by the AISKYEYE team at Lab of Machine Learning and Data Mining , Tianjin University, China. The benchmark dataset consists of 288 video clips formed by 261,908 frames and 10,209 static images, captured by various drone-mounted cameras, covering a wide range of aspects including location (taken from 14 different cities separated by thousands of kilometers in China), environment (urban and country), objects (pedestrian, vehicles, bicycles, etc.), and density (sparse and crowded scenes). Note that, the dataset was collected using various drone platforms (i.e., drones with different models), in different scenarios, and under various weather and lighting conditions. These frames are manually annotated with more than 2.6 million bounding boxes of targets of frequent interests, such as pedestrians, cars, bicycles, and tricycles. Some important attributes including scene visibility, object class and occlusion, are also provided for better data utilization.

The challenge mainly focuses on four tasks: 

(1) Task 1: object detection in images challenge. The task aims to detect objects of predefined categories (e.g., cars and pedestrians) from individual images taken from drones. 

(2) Task 2: object detection in videos challenge. The task is similar to Task 1, except that objects are required to be detected from videos.

(3) Task 3: single-object tracking challenge. The task aims to estimate the state of a target, indicated in the first frame, in the subsequent video frames.

(4) Task 4: multi-object tracking challenge. The task aims to recover the trajectories of objects in each video frame.


## Download

### Task 1: Object Detection in Images 

VisDrone2019-DET dataset

* trainset (1.44 GB): [BaiduYun](https://pan.baidu.com/s/1K-JtLnlHw98UuBDrYJvw3A) | [GoogleDrive](https://drive.google.com/file/d/1a2oHjcEcwXP8oUF95qiwrqzACb2YlUhn/view?usp=sharing)
    
* valset (0.07 GB):  [BaiduYun](https://pan.baidu.com/s/1jdK_dAxRJeF2Xi50IoML1g) | [GoogleDrive](https://drive.google.com/file/d/1bxK5zgLn0_L8x276eKkuYA_FzwCIjb59/view?usp=sharing)
    
* testset-dev (0.28 GB): [BaiduYun](https://pan.baidu.com/s/1RdRfSWV-1IFK7aWljLU_LQ) | [GoogleDrive](https://drive.google.com/open?id=1PFdW_VFSCfZ_sTSZAGjQdifF_Xd5mf0V)
    
* testset-challenge (0.28 GB): [BaiduYun](https://pan.baidu.com/s/1lvEkCgy1WWK4B7TLki4yBQ) | [GoogleDrive](https://drive.google.com/file/d/1KN8R3oioOvSXH492GEVk-Hx74nWHAcXT/view?usp=sharing)
    
VisDrone2019-DET toolkit: 

* [Matlab beta](https://github.com/VisDrone/VisDrone2018-DET-toolkit)

### Task 2: Object Detection in Videos

VisDrone2019-VID dataset

* trainset (7.53 GB):  [BaiduYun](https://pan.baidu.com/s/1kC3NTK6MPVv3D1CY9gXaCQ) | [GoogleDrive](https://drive.google.com/file/d/1NSNapZQHar22OYzQYuXCugA3QlMndzvw/view?usp=sharing)
    
* valset (1.49 GB):  [BaiduYun](https://pan.baidu.com/s/12-A6Mg1Gg7hyS4WwG27dDw) | [GoogleDrive](https://drive.google.com/file/d/1xuG7Z3IhVfGGKMe3Yj6RnrFHqo_d2a1B/view?usp=sharing)
    
* testset-dev (2.14 GB):  [BaiduYun](https://pan.baidu.com/s/1r1P5aJ1zOlQH_58LfYFzQQ) | [GoogleDrive](https://drive.google.com/open?id=1-BEq--FcjshTF1UwUabby_LHhYj41os5)
    
* testset-challenge (2.70 GB):  [BaiduYun](https://pan.baidu.com/s/1ew6B-kvKV9yv__onnjA4dQ) | [GoogleDrive](https://drive.google.com/file/d/1Qwyp_cEpGyXGqJ8IbusEzuNHgbM403NP/view?usp=sharing) 
    
VisDrone2019-VID toolkit: 

* [Matlab beta](https://github.com/VisDrone/VisDrone2018-VID-toolkit)

### Task 3: Single-Object Tracking 

VisDrone2019-SOT dataset

* trainset_part1 (7.78 GB):   [BaiduYun](https://pan.baidu.com/s/1obWeT5DvBkTuBmO1NlSQ-Q) | [GoogleDrive](https://drive.google.com/file/d/1a-AmQjYATzj8seXLlEm9Sx8aQmClrJka/view?usp=sharing)
    
* trainset_part2 (12.59 GB):  [BaiduYun](https://pan.baidu.com/s/1c6iZeMJUXOIERxFJJ6B0jw) | [GoogleDrive](https://drive.google.com/file/d/16YPyhNDQrTgW8I2HaH_HNEO-KTRA-xso/view?usp=sharing)
    
* valset (1.29 GB):   [BaiduYun](https://pan.baidu.com/s/1WTWx4iyf33lnIyRu2uP_Hg) | [GoogleDrive](https://drive.google.com/file/d/18SNAOlCJtApnG2m45ud-1e_OtGYill0D/view?usp=sharing)
    
* testset-dev (11.27 GB):  [BaiduYun](https://pan.baidu.com/s/18j3umaWR_1fFy2ISOe9dGg) | [GoogleDrive](https://drive.google.com/open?id=1xCiHjU4JlR9QsYtiHYy2UUd3m6NthoBC)
    
* testset-challenge_part1 (17.40 GB):  [BaiduYun](https://pan.baidu.com/s/14eWyaisDeciip-4_B14law) | [GoogleDrive](https://drive.google.com/file/d/1zxMLZrkkz4BkufbaDXQVMpDz-PRpPpxs/view?usp=sharing)
    
* testset-challenge_part2 (17.31 GB):  [BaiduYun](https://pan.baidu.com/s/1WDQ4JD5eLfRy-KVNyvKPig) | [GoogleDrive](https://drive.google.com/file/d/13J_9rwpf2TpVVsWgzMUv4uCxpOKDNbef/view?usp=sharing)
    
* testset-challenge_initialization(12 KB):  [BaiduYun](https://pan.baidu.com/s/1hvY0LXjTeuF8r-VVvVX1OQ) | [GoogleDrive](https://drive.google.com/file/d/1z7lQ0co8Dcu-ZojMN7dnIxn-i6QbGNL4/view?usp=sharing)
    
VisDrone2019-SOT toolkit: 

* [Matlab beta](https://github.com/VisDrone/VisDrone2018-SOT-toolkit)
    
### Task 4: Multi-Object Tracking 

VisDrone2019-MOT dataset

* trainset (7.53 GB):  [BaiduYun](https://pan.baidu.com/s/16BtpKNWi0cEk8WUtfzpEHQ) | [GoogleDrive](https://drive.google.com/file/d/1-qX2d-P1Xr64ke6nTdlm33om1VxCUTSh/view?usp=sharing)
    
* valset (1.48 GB):  [BaiduYun](https://pan.baidu.com/s/1wTWFpHw4uLXPVCp1m5fQNQ) | [GoogleDrive](https://drive.google.com/file/d/1rqnKe9IgU_crMaxRoel9_nuUsMEBBVQu/view?usp=sharing)
    
* testset-dev (2.14 GB):  [BaiduYun](https://pan.baidu.com/s/1_gLvMxkMKb3RZjGyZv7btQ) | [GoogleDrive](https://drive.google.com/open?id=14z8Acxopj1d86-qhsF1NwS4Bv3KYa4Wu)
    
* testset-challenge (2.70 GB):  [BaiduYun](https://pan.baidu.com/s/1xIloIRSj1FtcEoWI9esn7w) | [GoogleDrive](https://drive.google.com/file/d/1I0nn6dVKctzDE5YJ3q9qOlhKLiSIDAxF/view?usp=sharing)
    
VisDrone2019-MOT toolkit:

* [Matlab beta](https://github.com/VisDrone/VisDrone2018-MOT-toolkit)


## Citation 

@article{zhu2018vision,

  title={Vision meets drones: A challenge},
  
  author={Zhu, Pengfei and Wen, Longyin and Bian, Xiao and Ling, Haibin and Hu, Qinghua},
  
  journal={arXiv preprint arXiv:1804.07437},
  
  year={2018}
}


