# ECTLO
ECTLO is pure LiDAR odometry to tackle the challenges in Solid State LiDAR, including serve motion distortion, small field of view, and sparse scanning pattern. To account for the noisy data, a filter-based point-to-plane Gaussian Mixture Model is used for robust registration instead of the conventional ICP algorithm. Moreover, a continuous-time motion model is employed to relieve the inevitable distortions. The map maintenance is accomplished in one range image, making our odometry efficient on GPU.

**Pipeline**
![pipeline](https://user-images.githubusercontent.com/25858658/175489330-7037dab5-0071-4d48-99d9-3c7834851b23.png)
**Video demo of mapping result on different LiDARs** [Youtube](https://youtu.be/y3ZQZq_PaxA) [Bilibili](https://www.bilibili.com/video/BV1zL4y1A7Kn?share_source=copy_web)

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/y3ZQZq_PaxA/0.jpg)](http://www.youtube.com/watch?v=y3ZQZq_PaxA)

## Related paper
- Zheng, Xin and Jianke Zhu. “Effective Solid State LiDAR Odometry Using Continuous-time Filter Registration.” [arxiv](https://arxiv.org/abs/2206.08517)
```
@article{Zheng2022EffectiveSS,
  title={Effective Solid State LiDAR Odometry Using Continuous-time Filter Registration},
  author={Xin Zheng and Jianke Zhu},
  journal={ArXiv},
  year={2022},
  volume={abs/2206.08517}
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
