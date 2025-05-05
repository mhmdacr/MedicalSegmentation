# Medical Image Segmentation with U-Net (ResNet18 Encoder)

This project implements a **Medical Image Segmentation** pipeline using a U-Net architecture with a ResNet18 encoder. The model is applied to the **MedSegBench Ultrasound Nerve Dataset** for binary segmentation tasks.

## Features
- **U-Net Architecture**:
   - ResNet18 as the encoder (pretrained on ImageNet).
   - Custom upsampling decoder blocks.
- **Loss Functions**:
   - Binary Cross Entropy (BCE) with Dice Loss for better segmentation accuracy.
- **Training Pipeline**:
   - TensorBoard integration for loss/accuracy visualization.
   - Best model saving based on validation loss.
   - Early stopping and learning rate scheduling.
- **Evaluation**:
   - Metrics: Dice Score, IoU, Precision, Recall, and Accuracy.
   - Visualization: Input images, predicted masks, ground truth masks, and error maps.

---
