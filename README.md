# Benchmarking Loop Closure-Based LOAM Algorithms on Kitti Dataset

This repository contains research work that compares different loop closure-based LOAM algorithms. The configuration files for the algorithms have been modified to work with the Kitti dataset. Additionally, many of the algorithms did not generate a final odometry pose for each frame of the algorithm. In the submodules provided for each algorithm, a result parameter has been added to generate the output, which can be used to evaluate and compare the results of different algorithms using tools like evo or kitti_odom_eval.

## Acknowledgements

Thanks to the authors of LOAM, A-LOAM, LeGO LOAM, SC-A-LOAM, and SC-Lego-LOAM. The major codes in this repository have been borrowed from their efforts.
