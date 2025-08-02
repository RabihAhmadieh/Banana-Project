# The Banana Project from Udacity

In this project, you will need **Python 3.6** and the **unityagents** package installed before running the code.

> **Note:** This work was done using the Windows operating system and Anaconda software.

## Environment Setup

Create a virtual environment in Anaconda:

```bash
conda create -n DQN python=3.6
conda activate DQN
```

## Getting Started

Install the required libraries:

```bash
pip install unityagents
conda install matplotlib
conda install pytorch torchvision
```

## Project Details

- The state space has **37 states**.
- The action space has **4 actions**:
  - `0` – Move forward
  - `1` – Move backward
  - `2` – Turn left
  - `3` – Turn right

The task is episodic. To solve the environment, the agent must achieve an **average score of +13** over 100 consecutive episodes.

## Instructions

- To run the project, open `my_solution.ipynb` and run the cells to see the implementation using DQN.
- To view the double DQN implementation, open `my_double.ipynb` and run the cells.
