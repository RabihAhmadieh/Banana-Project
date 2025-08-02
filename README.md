{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "ceca556d-9f3b-405b-8936-5a0f44832145",
   "metadata": {},
   "source": [
    "# The Banana Project from UDacity\n",
    " In this project you will need *python* 3.6 and *unityagents* to be installed before running the code\n",
    "First of all lets make a virtual environment and call it DQN in anaconda: <br>\n",
    "Note: This work was done using wondows operating system and anaconda software."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "1a89f8c3-2ceb-4699-9070-8e56edd5a843",
   "metadata": {},
   "outputs": [],
   "source": [
    "conda create -n DQN python=3.6\n",
    "conda activate DQN"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "98ced740-6a5d-4066-b65f-0915da8b0f74",
   "metadata": {},
   "source": [
    "## Getting Started\n",
    "#### Installing the required libraries:\n",
    "Please enter the installation code mentioned below in order to be able to run the code:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "c08f4316-db86-4edf-be3c-5bf355120c6d",
   "metadata": {},
   "outputs": [],
   "source": [
    "pip install unityagents\n",
    "conda install matplotlib\n",
    "conda install pytorch torchvision"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "aa70840a-30b0-4216-8ae3-2db26b843d03",
   "metadata": {},
   "source": [
    "### Project Details:\n",
    "In this project we have 37 **sates** in the state space.<br>\n",
    "Also we have 4 **actions**:<br>\n",
    "0 - move forward.<br>\n",
    "1 - move backward.<br>\n",
    "2 - turn left.<br>\n",
    "3 - turn right.<br>\n",
    "\n",
    "The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "419148c8-2f6b-4b15-b953-58639a050020",
   "metadata": {},
   "source": [
    "### Instructions:\n",
    "To run the project open *my_solution.ipynb* after installing the above libraries and run the cells which will give the solution for the project using DQN.<br>\n",
    "Open *my_double.ipynb* and run the cells to see the solution using double DQN.<br>"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "414e772e-6622-4702-9f35-509ce60cb734",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
