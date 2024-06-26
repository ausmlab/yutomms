# YUTO MMS: A Comprehensive SLAM Dataset for Urban Mobile Mapping with Tilted LiDAR and Panoramic Camera Integration

The York University Teledyne Optech (YUTO) Mobile Mapping System (MMS) Dataset, encompassing four extensive sequences totalling 18.9 kilometres, was thoroughly assembled through two data collection expeditions on August 12,
2020, and June 21, 2019. Acquisitions were performed using a uniquely equipped vehicle, fortified with a panoramic camera, a tilted LiDAR, a Global Positioning System (GPS), and an Inertial Measurement Unit (IMU), journeying through
two strategic locations: the York University Keele Campus in Toronto and the Teledyne Optech headquarters in City of Vaughan, Canada. This is a robust benchmark of prevailing Simultaneous Localization and Mapping (SLAM) systems. 
This dataset was created by a team of [AUSM Lab](https://gunhosohn.me/).

For more details check out our [paper](https://journals.sagepub.com/doi/10.1177/02783649241261079), and [website](https://ausmlab.github.io/yutomms/).


* **Key Links**
	* **YUTO MMS Dataset**: [Download](https://ausmlab.github.io/yutomms/download.html)
	* **Paper**: ["YUTO MMS: A Comprehensive SLAM Dataset for Urban Mobile Mapping with Tilted LiDAR and Panoramic Camera Integration"](https://journals.sagepub.com/doi/10.1177/02783649241261079)
	* **Models Code**: [MaverickProjectLidar2Image](https://github.com/yujiazhang777/MaverickProjectLidar2Image)
	* **Website**: [YUTO MMS](https://ausmlab.github.io/yutomms/)


## Question Answering Datasets

* The YUTO MMS dataset contains questions: 
	* **SLAM**: [PVL-Cartographer](https://www.mdpi.com/2072-4292/15/13/3383)
	
## Data Description

### Datasets


* Sequence A: 324 m, one small loop.
* Sequence B: 7035 m, one large loop and a few small loops.
* Sequence C: 9137 m, many medium-size loops.
* Sequence D: 3634 m, a few loops.

### Data Format

* GNSS:
	* IMU.csv:
		* **``ax, ay, az``**: acceleration.
		* **``gx, gy, gz``**: angular rate.
	* GPS.csv:
		* **``"latitude"``**: .
		* **``"longitude"``**: .
                                * **``"altitude"``**: .

* Panoramic images: .jpg.
* Lidar scans: .bin.
	

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

YUTO MMS dataset is referenced [here](https://journals.sagepub.com/doi/10.1177/02783649241261079).  
