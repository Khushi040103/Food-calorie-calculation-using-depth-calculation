# Food-calorie-calculation-using-depth-calculation

🔍 Food Analysis Pipeline
This project presents a complete deep learning pipeline for food detection, classification, segmentation, and volume estimation. The system integrates multiple stages to analyze food from images using state-of-the-art models.

Key Components:
Classification: Fine-tuned Inception-ResNet-V2 on Food-101 and Recipe-1M datasets, using multi-GPU training with TFRecord preprocessing.

Segmentation: RefineNet architecture (pretrained on PASCAL VOC 2012) fine-tuned on manually labeled food data to produce pixel-level food masks.

Volume Estimation: Depth estimation model pretrained on NYU-Depth V2 generates depth maps; combined with segmentation and plate diameter for food volume calculation.

This end-to-end pipeline is ideal for nutrition tracking, food monitoring, and robotics applications in the food industry.
