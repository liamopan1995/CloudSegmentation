# CLoud Segmentation of stems and ground especially for SLAM in forestry environments

A modified version of Patchworkpp with additional code for Stem Segmentation

## Introduction

This project is an extension of the Patchworkpp library, which provides ground segmentation functionality. In addition to ground segmentation, this modified version includes code that enables the segmentation of tree stems or trunks.

The original Patchworkpp library can be found at [Patchwork++ ROS](https://github.com/original_repository_link). Please refer to the original repository for more information about Patchworkpp.

## Features

- Ground segmentation: Utilize Patchworkpp's ground segmentation functionality to identify and extract ground points from a point cloud.
- Stem segmentation: Build upon Patchworkpp to include code that can extract tree stems or trunks from the point cloud data.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:

place it under /catkin_ws/src
  <pre>
cd ~/catkin_ws
git clone
  </pre>

2. Install the required dependencies. 
PCL, ROS, Eigen
3. Build the project:
  <pre>
cd ~/catkin_ws
catkin_make
  </pre>

5. Run the application:
  <pre>
cd ~/catkin_ws
source devel/setup.bash
roslaunch patchworkpp CloudSegmentation.launch
  </pre>

## Usage


## License

 no license has been specified yet. However, it is subjected to the license in [patchworkpp ros](https://github.com/original_repository_link).

## Acknowledgments

This project is built upon the work of the original Patchworkpp library. Thanks to the contributors of Patchworkpp for their valuable contributions.





