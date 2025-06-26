## Flood Area Segmentation using Deep Learning

This project involves segmenting flood-affected regions from satellite images using a U-Net-based Convolutional Neural Network. The main objective is to support disaster management and emergency planning by accurately identifying waterlogged areas in flood-hit zones.

## Dataset

The dataset contains 290 satellite images along with manually annotated binary masks. The masks were created using Label Studio, an open-source data labeling tool. Each mask highlights the water regions present in the corresponding flood image. The task is to train a segmentation model that can predict these regions accurately on new, unseen images.

## Model Architecture

Base Model: U-Net

Input Size: 128×128 pixels

Output: Binary segmentation mask (flood vs. non-flood)

Loss Function: Binary Cross-Entropy

Optimizer: Adam

Evaluation Metrics: Accuracy, IoU (Intersection over Union)

## Results

The model achieved good segmentation performance on the test set. It successfully highlights flood-affected areas and performs well in terms of both pixel-level accuracy and IoU score.

## Future Work

Possible future improvements include using multi-temporal or multi-spectral satellite imagery to enhance model accuracy. Increasing the dataset size and incorporating data from different flood events can also improve generalization.

