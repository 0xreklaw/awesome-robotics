<div align="center">
  <h1 align="center">Based Robotics</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="https://github.com/ventali/awesome-zk/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/0xreklaw/awesome-robotics">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">A curated list of awesome robotics resources, libraries, tools, and more. </p>
</div>

# Table of Contents

* [Learning](#Learning)
* [Projects](#Projects)
* [Data Sets](#Data-Sets)
* [Simulation](#Simulation)
* [People](#People)
* [Companies](#Companies)

# Learning

## Videos
- [CMU Robot Dynamics](https://www.youtube.com/watch?v=LiNgr1tz49I&list=PLZnJoM76RM6ItAfZIxJYNKdaR_BobleLY)
- [DeepMind Introduction to RL](https://www.youtube.com/watch?v=TCCjZe0y4Qc&list=PLqYmG7hTraZCRwoyGxvQkqVrZgDQi4m-5)
- [Deep Reinforcement Learning UC Berkeley](https://rail.eecs.berkeley.edu/deeprlcourse/)
- [CS231n Deep Learning for Computer Vision Stanford](https://cs231n.stanford.edu/)

## Reading
- [Underactuated Robotics](https://underactuated.csail.mit.edu/)
- [Robotic Manipulation](https://manipulation.csail.mit.edu/)
- [ORB-SLAM](https://arxiv.org/pdf/1502.00956)
- [Say-Can](https://say-can.github.io/)
- [ACT Model](https://tonyzhaozh.github.io/aloha/)

# Projects

### [Low Cost Robot](https://github.com/AlexanderKoch-Koch/low_cost_robot)

The low-cost robot arm adapts the ACT model, making it easy to set up and use.

### [UMI Gripper](https://umi-gripper.github.io/)

A data collection policy and framework that easily enables the transfer of skills from real world human interaction to robot manipulation.

### VR Teleoperation

Similar repo's on teleoperation via VR headsets. Current support is only for Meta and Apple headsets

- [Open-TeleVision](https://github.com/OpenTeleVision/TeleVision)
- [VisionPro Teleop](https://github.com/Improbable-AI/VisionProTeleop)

# Data Sets

### [Open X-Embodiment (RT-X)](https://robotics-transformer-x.github.io/)
- RoboCasa is a large-scale simulation framework for training generally capable robots to perform everyday tasks.

### [RoboCasa](https://robocasa.ai/)
- RoboCasa is a large-scale simulation framework for training generally capable robots to perform everyday tasks.

# Simulation

### Physics Engines
- MuJoCo
- PyBullet

### Simulators
- Isaac Sim

### Frameworks
- Gymnasium
- Isaac Gym

# Single Board Computers (SBCs)

## [Raspberry Pi](https://www.amazon.com/Raspberry-Pi-Quad-core-Cortex-A76-Processor/dp/B0CTQ3BQLS/ref=sr_1_2_sspa?crid=1UFOSCMJMYBQM&dib=eyJ2IjoiMSJ9.tbZ0EMR289jYGuOEXI8_Rh7ZFivo67gudYLC4ENELtvWaic-gE_ceTOLyl__9r0Olv89eUoqlc4KbQIboEtVYatlThzGexyqlfEDNuzae9WHedzPpH3oTADxY2DMXBsqUvtu7jMO4oSq-bYm3R5cRXDGGnPwJknUQ_IUwug1UthwMevAhQzVhERAIuFhfXG5_9WN6bsEZdTpm6enhpZRTdLbId_-8TCiTG3yz5WJZeHP2tj8ci46qGQJtlXymPp0V-MMbff5I0JQ3g1o51uaADEXO2tmrtFdSnxR3l4mF2c.7eAQpYtWXQE4PEnbtdBXpFuIADtu0KQkGfK0KNWkg-o&dib_tag=se&keywords=raspberry+pi+5&qid=1716497131&s=electronics&sprefix=raspberr%2Celectronics%2C170&sr=1-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)

**Parts Not Included:**

- HDMI Cable
- Micro SD Card
- Power Supply

## Setup:

### 1. Download the Raspberry Pi Imager:

- Visit the [Raspberry Pi website](https://www.raspberrypi.org/software/) and download the Raspberry Pi Imager for your operating system (Windows, macOS, or Linux).
- Install the Raspberry Pi Imager on your computer.

### 2. Prepare the Micro SD Card:

- Insert the Micro SD Card into your computer.
- Open the Raspberry Pi Imager.
- Choose the operating system you want to install (e.g., Raspberry Pi OS).
- Select the Micro SD Card as the storage device.
- Click "Write" to flash the operating system onto the Micro SD Card.
- Once flashing is complete, safely eject the Micro SD Card from your computer.

### 3. Set Up the Hardware:

- Insert the flashed Micro SD Card into the appropriate slot on your Raspberry Pi.
- Connect the HDMI Cable from the Raspberry Pi to your monitor.
- Connect a USB keyboard and mouse to the Raspberry Pi.
- Plug in the power supply to the Raspberry Pi.

### 4. Initial Boot:

- Power on the Raspberry Pi by connecting it to a power source.
- Wait for the initial boot process to complete, which may take several minutes.
- Follow the on-screen prompts to complete the initial setup, including setting up Wi-Fi, username, and password.

### 5. Update and Upgrade:

- Open a terminal window on the Raspberry Pi.
- Run the following commands to update and upgrade the system packages:
  ```sh
  sudo apt-get update
  sudo apt-get upgrade
  ```

## [Nvidia Jetson](https://www.amazon.com/dp/B0BZJTQ5YP?nvid=em-945-13766-0005-000&th=1)

**Parts Not Included:**

- Display Port Cable
- Micro SD Card

## Setup:

### 1. Flash Linux onto your Jetson:

- Visit the [JetPack SDK page](https://developer.nvidia.com/embedded/jetpack) and download the latest version of JetPack.
- Follow the installation directions provided on the page.
- If you encounter issues with Linux booting, install and run [JetPack 5.1.3](https://developer.nvidia.com/embedded/jetpack-archive).

### 2. Prepare the Micro SD Card:

- Insert the Micro SD Card into your computer.
- Use an imaging tool (e.g., Etcher, Rufus) to flash the downloaded JetPack image onto the Micro SD Card.
- Once flashing is complete, safely eject the Micro SD Card from your computer.

### 3. Set Up the Hardware:

- Insert the flashed Micro SD Card into the appropriate slot on your Jetson device.
- Connect the Display Port Cable from the Jetson to your monitor.
- Connect a USB keyboard and mouse to the Jetson.
- Plug in the power supply to the Jetson.

### 4. Initial Boot:

- Power on the Jetson by connecting it to a power source.
- Wait for the initial boot process to complete, which may take several minutes.
- Follow the on-screen prompts to complete the initial setup, including setting up Wi-Fi, username, and password.

### 5. Update and Upgrade:

- Open a terminal window on the Jetson.
- Run the following commands to update and upgrade the system packages:
  ```sh
  sudo apt-get update
  sudo apt-get upgrade
  ```

# Based People

- [Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/)
- [Tony Zhao](https://tonyzhaozh.github.io/)
- [Michael Equi](https://x.com/michael_equi)
- [Karol Hausman](https://karolhausman.github.io/)
- [Vikash Kumar](https://vikashplus.github.io/)
- [Chelsea Finn](https://ai.stanford.edu/~cbfinn/)

# Based Companies

- Boston Dynamics
- Tesla
- Physical Intelligence
- K-Scale
- Figure AI
- Apptronik
- Sanctuary AI
- Agility Robotics
- Unitree
- Tau Robotics

