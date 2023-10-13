# Class-Activation-Mapping-
Class Activation Mapping (CAM) is a technique used in deep learning to visualize which regions of an image are being used by the model for its predictions.

## Overview
Purpose: To understand which parts of an image influence a model's decision.
Core Principle: Uses weights from the final layers of a CNN to produce a heatmap that can be superimposed on the original image.
Applications: Model interpretability, debugging, and enhancing transparency in model decision-making.

## How CAM Works
Global Average Pooling: Instead of traditional fully connected layers, a Global Average Pooling (GAP) layer condenses the spatial information of feature maps into a vector, which is then used for classification.

Weighted Feature Maps: The model's prediction for a particular class relies on specific weighted feature maps. CAM leverages these weights to create a heatmap.

Visualization: The resultant heatmap can be placed over the original image, providing a clear view of regions the model finds significant

# Conclusion
CAM serves as a bridge between the complex computations of CNNs and tangible visual interpretations.
