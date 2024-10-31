# AI Course Project: Semantic Segmentation and Reinforcement Learning

This repository contains project work for an Artificial Intelligence course. The project is divided into two parts:
1. **Image Semantic Segmentation**: Implementing U-Net and Attention U-Net.
2. **Reinforcement Learning for Control**: Using the Actor-Critic algorithm to balance a standing pen on a surface by moving it in a 1D dimension.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Part 1: Image Semantic Segmentation](#part-1-image-semantic-segmentation)
  - [U-Net Architecture](#u-net-architecture)
  - [Attention U-Net Architecture](#attention-u-net-architecture)
- [Part 2: Reinforcement Learning for Control](#part-2-reinforcement-learning-for-control)
  - [Actor-Critic Algorithm](#actor-critic-algorithm)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

This project covers two fundamental AI techniques:
1. **Image Semantic Segmentation**: Applying U-Net and Attention U-Net models for segmenting images into meaningful parts.
2. **Reinforcement Learning for Dynamic Control**: Using Actor-Critic reinforcement learning to balance a vertical pen on a flat, movable surface by learning optimal balancing actions.

Each part of the project is implemented as a Jupyter notebook, allowing easy code review, experimentation, and visualization.

---

## Part 1: Image Semantic Segmentation

### U-Net Architecture
U-Net is a deep learning model designed for biomedical image segmentation. It follows an encoder-decoder structure with skip connections that improve segmentation accuracy by preserving spatial information.

Key features include:
- **Downsampling Encoder**: Extracts high-level features by reducing spatial resolution.
- **Upsampling Decoder**: Reconstructs the original image resolution with high segmentation accuracy.
- **Skip Connections**: Retain information across the network for precise boundary segmentation.

### Attention U-Net Architecture
The Attention U-Net builds on U-Net by incorporating attention mechanisms. This improves segmentation by focusing on the most relevant image regions.

Key features include:
- **Attention Gates**: Identify and prioritize important features.
- **Enhanced Performance**: Helps to ignore irrelevant background details for more accurate segmentation.

---

## Part 2: Reinforcement Learning for Control

### Actor-Critic Algorithm
This notebook implements the **Actor-Critic** algorithm, a popular reinforcement learning approach, to balance a pen standing vertically by moving a surface horizontally.

- **Objective**: Train an agent to keep the pen balanced by learning actions that move the surface to maintain equilibrium.
- **Actor**: Selects actions based on the current state.
- **Critic**: Evaluates the chosen action by estimating the expected future reward.
  
The algorithm is implemented to dynamically adjust actions in real-time, demonstrating continuous control using reinforcement learning principles.

---

## Installation

To run the notebooks, follow these steps:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/alrezmlk/AI-project-Spring2024/
   cd ai-course-project

