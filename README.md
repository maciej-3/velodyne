# This fork

In the original repo, `velodyne_pointcloud` is always timestamped according to either the beginning or the end of the revolution of Velodyne lidars. This fork changes this behaviour in such a way that these timestmaps are always synced with the points in front of the sensor. If you would like to project lidar points onto a camera space that is also facing the front, then this repo can help to reduce the discrepancy of the projection when your senors are moving.


---

[![](https://github.com/ros-drivers/velodyne/workflows/Basic%20Build%20Workflow/badge.svg)](https://github.com/ros-drivers/velodyne/actions)

Overview
========

Velodyne<sup>1</sup> is a collection of ROS<sup>2</sup> packages supporting `Velodyne high
definition 3D LIDARs`<sup>3</sup>.

**Warning**:

  The master branch normally contains code being tested for the next
  ROS release.  It will not always work with every previous release.
  To check out the source for the most recent release, check out the
  tag `<version>` with the highest version number.

The current ``master`` branch works with ROS Kinetic and Melodic.
CI builds are currently run for Kinetic and Melodic.

- <sup>1</sup>Velodyne: http://www.ros.org/wiki/velodyne
- <sup>2</sup>ROS: http://www.ros.org
- <sup>3</sup>`Velodyne high definition 3D LIDARs`: http://www.velodynelidar.com/lidar/lidar.aspx
