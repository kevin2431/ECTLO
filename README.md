# ECTLO
ECTLO is pure LiDAR odometry to tackle the challenges in Solid State LiDAR, including serve motion distortion, small field of view, and sparse scanning pattern. To account for the noisy data, a filter-based point-to-plane Gaussian Mixture Model is used for robust registration instead of the conventional ICP algorithm. Moreover, a continuous-time motion model is employed to relieve the inevitable distortions. The map maintenance is accomplished in one range image, making our odometry efficient on GPU.

**Pipeline**
