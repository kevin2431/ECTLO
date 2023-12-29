# ECTLO
ECTLO is pure LiDAR odometry to tackle the challenges in Solid State LiDAR, including serve motion distortion, small field of view, and sparse scanning pattern. To account for the noisy data, a filter-based point-to-plane Gaussian Mixture Model is used for robust registration instead of the conventional ICP algorithm. Moreover, a continuous-time motion model is employed to relieve the inevitable distortions. The map maintenance is accomplished in one range image, making our odometry efficient on GPU.

**Pipeline**
![pipeline](https://user-images.githubusercontent.com/25858658/175489330-7037dab5-0071-4d48-99d9-3c7834851b23.png)
**Video demo of mapping result on different LiDARs** [Youtube](https://youtu.be/y3ZQZq_PaxA) [Bilibili](https://www.bilibili.com/video/BV1zL4y1A7Kn?share_source=copy_web)

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/y3ZQZq_PaxA/0.jpg)](http://www.youtube.com/watch?v=y3ZQZq_PaxA)

## Related paper
- Zheng, Xin and Jianke Zhu. “ECTLO: Effective Continuous-Time Odometry Using Range Image for LiDAR with Small FoV.” [arxiv](https://arxiv.org/abs/2206.08517), [IEEE](https://ieeexplore.ieee.org/abstract/document/10341592)
```
@inproceedings{zheng2023ectlo,
  title={ECTLO: Effective Continuous-Time Odometry Using Range Image for LiDAR with Small FoV},
  author={Zheng, Xin and Zhu, Jianke},
  booktitle={2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={9102--9109},
  year={2023},
  organization={IEEE}
}
```
- Data structure is based on our previous work ELO. 
Zheng, Xin, and Jianke Zhu. "Efficient LiDAR odometry for autonomous driving." IEEE Robotics and Automation Letters 6.4 (2021): 8458-8465. [arvix](https://arxiv.org/abs/2104.10879), [IEEE](https://ieeexplore.ieee.org/abstract/document/9531543)
```
@article{zheng2021efficient,
  title={Efficient LiDAR odometry for autonomous driving},
  author={Zheng, Xin and Zhu, Jianke},
  journal={IEEE Robotics and Automation Letters},
  volume={6},
  number={4},
  pages={8458--8465},
  year={2021},
  publisher={IEEE}
}
```

## Dataset
Our collected dataset in Yuquan Campus, Zhejiang University. 

[Google Drive](https://drive.google.com/drive/folders/1QF4mBRBP3TVcMF5eN_Urfj1WtXwkJ7mX?usp=sharing)

[Baidu Disk](https://pan.baidu.com/s/1xq5QCPpkwWxbyWqgl63p4A) (提取码: iauu)
