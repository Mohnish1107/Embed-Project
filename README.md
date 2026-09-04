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
| **System Update** | ✅ Done | System packages updated and upgraded |
| **ROS 2 Jazzy Installation** | ✅ Done | ROS 2 desktop packages installed |
| **ROS 2 Environment Setup** | ✅ Done | Environment variables configured in bashrc |
| **Python Dependencies** | ✅ Done | OpenCV and pip installed |
| **Verification Tests** | ✅ Done | Tests till now passed successfully |

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

## 🔧 Complete Setup Instructions

### Step 1: Update System Packages

First, update your system's package list and upgrade all installed packages to their latest versions:

```bash
sudo apt update && sudo apt upgrade -y
```

---

### Step 2: Install ROS 2 Jazzy

**For this you can go to the official documentation of ROS 2 Jazzy **

https://docs.ros.org/en/jazzy/Installation/Ubuntu-Install-Debs.html

---

### Step 3: Setup Environment Variables

Add ROS 2 to your bashrc file so it loads automatically in every terminal:

```bash
echo "source /opt/ros/jazzy/setup.bash" >> ~/.bashrc
source ~/.bashrc
```

**Expected Output:** No output, but ROS 2 will now be available in your terminal.

---

## ✅ Verification Tests

Run these tests to confirm everything is working correctly.

### Test 1: Check ROS 2 Version

```bash
ros2 --version
```

**Expected Output:** `ros2 jazzy`

---

### Test 2: Check Available ROS 2 Commands

```bash
ros2 -h
```

**Expected Output:** Display of all available ros2 commands (like run, topic, node, etc.)

---

### Test 3: List ROS 2 Packages

```bash
ros2 pkg list
```

```bash
gazebo --version
