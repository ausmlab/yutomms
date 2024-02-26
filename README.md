# YUTO MMS: A Comprehensive Mobile Mapping Dataset for Enhanced SLAM Research

he York University Teledyne Optech (YUTO) Mobile Mapping System (MMS) Dataset, encompassing four extensive sequences totalling 18.9 kilometres, was thoroughly assembled through two data collection expeditions on August 12,
2020, and June 21, 2019. Acquisitions were performed using a uniquely equipped vehicle, fortified with a panoramic camera, a tilted LiDAR, a Global Positioning System (GPS), and an Inertial Measurement Unit (IMU), journeying through
two strategic locations: the York University Keele Campus in Toronto and the Teledyne Optech headquarters in City of Vaughan, Canada. This is a robust benchmark of prevailing Simultaneous Localization and Mapping (SLAM) systems. 
This dataset was created by a team of [AUSM Lab](https://gunhosohn.me/).

For more details check out our paper ["YUTO MMS: A Comprehensive Multi-Sensor Dataset in Urban and Campus Environments for Enhanced SLAM Research"](https://arxiv.org/abs/2001.11770v1), and [website](https://ausmlab.github.io/yutomms/).



* **Key Links**
	* **YUTO MMS Dataset**: [Download](https://ausmlab.github.io/yutomms/download.html)
	* **Paper**: ["YUTO MMS: A Comprehensive Mobile Mapping Dataset for Enhanced SLAM Research"](https://www.researchgate.net/profile/Yujia-Zhang-29)
	* **Models Code**: [MaverickProjectLidar2Image](https://github.com/yujiazhang777/MaverickProjectLidar2Image)
	* **Website**: [YUTO MMS](https://ausmlab.github.io/yutomms/)


## Question Answering Datasets

* The YUTO MMS dataset contains questions: 
	* **SLAM**: [PVL-Cartographer](https://www.mdpi.com/2072-4292/15/13/3383)
	
## Data Description

### Datasets


* Sequence A: .
* Sequence B: .
* Sequence C: .
* Sequence D: .

### Data Format

* GNSS:
	* IMU.csv:
		* **``ax, ay, az``**: acceleration.
		* **``gx, gy, gz``**: angular rate.
	* GPS.csv:
		* **``"latitude"``**: .
		* **``"longitude"``**: .
                                * **``"altitude"``**: .

* Panoramic images:
* Lidar scans:
	

### Data Statistics

YUTO MMS question decomposition datasets:

| Data | Image format and nubmer | LiDAR format and number | IMU+GPS format |
|-----------|-------------------------|-------------------------|-------------------------|
| Sequence A | .jpg, 700     |     .bin, 1432      |    .csv, 11845    |
| Sequence B | .jpg, 8382    |    .bin, 17395     |     .csv, 143637    |
| Sequence C | .jpg, 10778  |    .bin, 22992     |     .csv,  189875  |
| Sequence D | .jpg, 4500     |    .bin, 9615       |   .csv, 79506    |


## Reference

```
@Article{rs15133383,
AUTHOR = {Zhang, Yujia and Kang, Jungwon and Sohn, Gunho},
TITLE = {PVL-Cartographer: Panoramic Vision-Aided LiDAR Cartographer-Based SLAM for Maverick Mobile Mapping System},
JOURNAL = {Remote Sensing},
VOLUME = {15},
YEAR = {2023},
NUMBER = {13},
ARTICLE-NUMBER = {3383},
URL = {https://www.mdpi.com/2072-4292/15/13/3383},
ISSN = {2072-4292},
DOI = {10.3390/rs15133383}
}
```

YUTO MMS dataset is referenced [here](https://www.researchgate.net/profile/Yujia-Zhang-29).  
