# Embed-Project
My team's first ROS and Gazebo based project for our Embeded System Course Project
# ROS 2 Environment Setup for Object Detection Project

## 📖 Project Overview

This repository documents the environment setup for our Embedded Systems course project on object detection using ROS 2 and Gazebo simulation. The project focuses on the software implementation of object detection pipelines within a simulated robotics environment.

**Project Type:** Embedded Systems Course - Object Detection Category  
**Platform:** Ubuntu 24.04 with ROS 2 Jazzy  
**Status:** Environment Setup Complete

---

## 🚀 Current Status (As of September 2026)

### ✅ Completed Tasks

| Task | Status | Description |
|------|--------|-------------|
| **Ubuntu Installation** | ✅ Done | Ubuntu 24.04 installed and configured |
| **ROS 2 Jazzy Installation** | ✅ Done | ROS 2 desktop packages installed |
| **Gazebo Installation** | ✅ Done | Gazebo Harmonic installed with ROS integration |
| **Development Tools** | ✅ Done | colcon, rosdep, vcstool installed |
| **Workspace Creation** | ✅ Done | ROS 2 workspace created at `~/ros2_ws` |
| **Environment Variables** | ✅ Done | ROS 2 added to bashrc for automatic loading |
| **Verification Tests** | ✅ Done | All tests passed successfully |

---

## 📋 Prerequisites

### System Requirements

- **Ubuntu 22.04 (Jammy) or 24.04 (Noble)**
- **Minimum 8GB RAM** (16GB recommended)
- **At least 20GB free disk space**
- **Stable internet connection**

### Required Software

| Software | Version | Purpose |
|----------|---------|---------|
| **ROS 2** | Jazzy Jalisco | Robotics framework |
| **Gazebo** | Harmonic | Simulation environment |
| **Python** | 3.10+ | Programming language |
| **Git** | Latest | Version control |

---

## 🔧 Setup Instructions

### Step 1: Update System Packages

```bash
sudo apt update && sudo apt upgrade -y
