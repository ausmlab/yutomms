## **YUTO MMS: A Comprehensive SLAM Dataset for Urban Mobile Mapping with Tilted LiDAR and Panoramic Camera Integration**

The York University Teledyne Optech (YUTO) Mobile Mapping System (MMS) Dataset, encompassing four extensive sequences totalling 20.1 kilometres, was thoroughly assembled through two data collection expeditions on August 12,
2020, and June 21, 2019. Acquisitions were performed using a uniquely equipped vehicle, fortified with a panoramic camera, a tilted LiDAR, a Global Positioning System (GPS), and an Inertial Measurement Unit (IMU), journeying through
two strategic locations: the York University Keele Campus in Toronto and the Teledyne Optech headquarters in City of Vaughan, Canada. This is a robust benchmark of prevailing Simultaneous Localization and Mapping (SLAM) systems. 
This dataset was created by a team of [AUSM Lab](https://gunhosohn.me/).


For more details on YUTO MMS dataset, please refer to our [paper](#paper).  

<center>
    <a href="https://github.com/ausmlab/yutomms/tree/main/images/maverick_route.jpg"> 
        <img src="images/maverick_route.jpg" height="170">
      </a>
</center>

## **Paper**

[**Zhang Y, Ahmadi S, Kang J, Arjmandi Z, Sohn G. YUTO MMS: A comprehensive SLAM dataset for urban mobile mapping with tilted LiDAR and panoramic camera integration. The International Journal of Robotics Research. 2024;0(0). doi:10.1177/02783649241261079**](https://journals.sagepub.com/doi/10.1177/02783649241261079)  


```markdown
@article{doi:10.1177/02783649241261079,
author = {Yiujia Zhang and SeyedMostafa Ahmadi and Jungwon Kang and Zahra Arjmandi and Gunho Sohn},
title ={YUTO MMS: A comprehensive SLAM dataset for urban mobile mapping with tilted LiDAR and panoramic camera integration},
journal = {The International Journal of Robotics Research},
volume = {0},
number = {0},
pages = {02783649241261079},
year = {0},
doi = {10.1177/02783649241261079},
URL = {https://doi.org/10.1177/02783649241261079},
eprint = {https://doi.org/10.1177/02783649241261079}
}

```
## **Authors**

<div>
<div class="card">
  <img src="images/authors/author_01.jpg" alt="Avatar" width="250" height="100">
  <div class="container">
    <a href="https://scholar.google.com/citations?hl=en&user=ww8ZXGEAAAAJ">
    <h4><b>Yujia Zhang</b></h4>  
    </a>
  </div>
    
</div>
<div class="card">
  <img src="images/authors/author_02.jpg" alt="Avatar" width="250" height="100">
  <div class="container">
    <a href="https://gunhosohn.me/mostafa-ahmedi/">
    <h4><b>SeyedMostafa Ahmadi</b></h4>  
    </a>
  </div>
    
</div>
<div class="card">
  <img src="images/authors/author_03.jpg" alt="Avatar" width="250" height="100">
  <div class="container">
    <a href="https://gunhosohn.me/jungwon-kang/">
    <h4><b>Jungwon Kang</b></h4>
    </a>
  </div>
    
</div>
<div class="card">
  <img src="images/authors/author_04.jpg" alt="Avatar" width="250" height="100">
  <div class="container">
    <a href="https://gunhosohn.me/zahra-arjmandi/">
    <h4><b>Zahra Arjmandi</b></h4>  
    </a>
  </div>
    
</div>
<div class="card">
  <img src="images/authors/author_05.jpg" alt="Avatar" width="250" height="100">
  <div class="container">
    <a href="https://gunhosohn.me/"> 
    <h4><b>Gunho Sohn</b></h4>  
    </a>
  </div> 
</div>
</div>


### **Dataset Description**

The directory structure of our YUTO MMS dataset is shown in the following figure.  

<center>
    <a href="https://github.com/ausmlab/yutomms/tree/main/images/YUTO-Dataset-directory-structure.JPG"> 
        <img src="images/YUTO-Dataset-directory-structure.JPG" height="400">
      </a>
</center>

**YUTO MMS dataset general information**

Sequence | Number of image files | Number of LiDAR scans | Number of GPS+IMU data | Total directory volume 
------------ | ------------- | ------------- | ------------- | ------------- 
A | 700 | 1432 | 11845 | 3.8 GB   
B | 8382 | 17395 | 143637 | 45.6 GB     
C | 10778 | 22992 | 189875 | 59.2 GB    
D | 4500 | 9615 | 79506 | 25.2 GB    

**Dataset Evaluation**

Sequence | ORB-SLAM2 | VINS | RPV-SLAM | HDPV-SLAM | LOAM | Cartographer | PVL-Cartographer 
------------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | -------------
A | 5.894 | 3.997 | 1.618  | 1.4 | Fail  | 4.023 | 0.766  
B | 100.870 | 86.897 | 12.910  | 9.58 | Fail  | 152.230 | 2.599  
C | 155.908 | 160.765 | 30.661  | 11.93 | Fail  | 183.619 | 3.739  
D | 10.665 | 12.875 | 5.673  | 4.69 | Fail  | 58.576 | 2.204  

**Our papers using YUTO MMS dataset**

M. Ahmadi, A. A. Naeini, M. M. Sheikholeslami, Z. Arjmandi, Y. Zhang and G. Sohn, "HDPV-SLAM: Hybrid Depth-Augmented Panoramic Visual SLAM for Mobile Mapping System with Tilted LiDAR and Panoramic Visual Camera," 2023 IEEE 19th International Conference on Automation Science and Engineering (CASE), Auckland, New Zealand, 2023, pp. 1-8, doi: 10.1109/CASE56687.2023.10260361.

Zhang, Yujia, Jungwon Kang, and Gunho Sohn. 2023. "PVL-Cartographer: Panoramic Vision-Aided LiDAR Cartographer-Based SLAM for Maverick Mobile Mapping System" Remote Sensing 15, no. 13: 3383. https://doi.org/10.3390/rs15133383

J. Kang, Y. Zhang, Z. Liu, A. Sit and G. Sohn, "RPV-SLAM: Range-augmented Panoramic Visual SLAM for Mobile Mapping System with Panoramic Camera and Tilted LiDAR," 2021 20th International Conference on Advanced Robotics (ICAR), Ljubljana, Slovenia, 2021, pp. 1066-1072, doi: 10.1109/ICAR53236.2021.9659458.

## **Download**

- To download the YUTO MMS dataset, [download YUTO MMS](/download.md).

## **News**

To get the udpates of YUTO dataset, [news](/news.md).

