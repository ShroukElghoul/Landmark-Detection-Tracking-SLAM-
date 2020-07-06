# Landmark-Detection-Tracking-SLAM
## Project Overview
This project is part of Udacity Computer Vision Nanodegree. It is an implementation of SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world.
It combines robot sensor measurements and movement updates to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.

Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot.
![](images/robot_world.png)

## Project Structure

The project is broken up into three Python notebooks and a robot class; the first two are for exploration of provided code.

Notebook 1 : Robot Moving and Sensing

Notebook 2 : Omega and Xi, Constraints

Notebook 3 : Landmark Detection and Tracking

robot_class.py

## Local Environment Installation Guide

$ git clone https://github.com/ShroukElghoul/Landmark-Detection-Tracking-SLAM-.git

$ sudo pip3 install -r requirements.txt

## Example Results
1) Robot
   Actual: [x=66.22893 y=83.21661]

   Predicted: [x=67.84919591053846, y=83.65808994916986]

2) Landmarks
   Actual: [[79, 67], [75, 84], [23, 20], [77, 34], [85, 11]]

   Predicted: [[77.339, 67.487], [74.228, 84.059], [21.696, 20.468], [75.940, 33.973], [84.258, 10.860]]

