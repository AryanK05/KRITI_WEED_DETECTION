# Semi-Supervised Weed Detection

This repository contains code for the **Semi-Supervised Weed Detection** challenge. The objective of this project is to develop a weed detection model using **semi-supervised learning** techniques to identify and localize weeds in agricultural images. The model leverages both labeled and unlabeled data for improved accuracy.

## Problem Statement

The challenge is focused on:
- A small labeled dataset with 200 images containing sesame crops and weeds.
- A large unlabeled dataset with 1000 images of sesame crops and weeds.
- A test dataset containing 100 images and corresponding annotations.

The goal is to use both labeled and unlabeled data for training a robust model to detect weeds in agricultural fields.

https://drive.google.com/file/d/1tuvC3TF4hD7ho6Zpvrh9Xsj-IeCFoTcY/view?usp=drive_link  THis is the link for model files

## Installation

Before running any scripts, you need to install the required dependencies. Make sure you have Python 3.7 or higher installed. ALso run the below command before running notebook
```bash
pip install ultralytics
```
Also, in the notebook itself , update the directory of data , because this notebook was made in kaggle . Here is the link to Kaggle for this notebook , where everything is explained in detail --

https://www.kaggle.com/code/aryankaushik005/weed-deetection-yolo-final

### Step 1: Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/weed-detection.git
cd weed-detection
