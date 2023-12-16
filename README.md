# R2-D2 and BB-8 Detection (Star Wars)

Based on open-source project by Antonio Verdone

You can read more at (https://averdones.github.io/tensorflow-object-detection-star-wars/)

## Results
<p align="center">
  <img src="results/result_2.gif">
</p>

## Project Overview

This project demonstrates the implementation of a custom object detection task using TensorFlow's Object Detection API. The primary focus is on detecting specific objects, namely R2-D2 and BB-8, in both images and videos. The key technique applied in this project is transfer learning, which involves using a pre-trained Convolutional Neural Network (CNN) as the starting point for training a new model.

## Key Components:

label_map_path: Path to label map file.

data_dir: Directory with images and annotations.

output_dir: Directory for TF Records.

pipeline_config_path: Configuration file path.

train_dir: Training-related files directory.

trained_checkpoint_prefix: Checkpoint file prefix.

output_directory: Directory for the exported frozen graph.

## Tools and Languages:

Python: Primary scripting language.

TensorFlow's Object Detection API: Visualization tool for training.

Pre-trained Model: ssd_inception_v2_coco.

Jupyter Notebook
