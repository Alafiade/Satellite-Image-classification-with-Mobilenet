# Satellite-Image-classification-with-Mobilenet
# Overview
This project demonstrates the fine-tuning ofa pretrained MobileNet architecture for an image classification task.
The primary focus was on achieving high accuracy through effetive optimization techniques and performance evaluation.

# Dataset Description
. Source: The dataset used in this project consisted of 4 diffferent classes mixed fromSensors and google map snapshot.
        and was gotten from the Kaggle website.
. Preprocessing :  Images were resized to match MobileNet's inpout requirements  and normalized for optimal performance.
. Split : Data was divided into training and validation sets to evaluate the model's generalization capabilities.

# Implementation Details
1. Model Architecture:
   . Base Model: Pretrained MobileNet.
   . Width Multiplier: 0.1.
   . Regularization: Added a dropout layer with a probability of 0.3 to reduce overfitting.
2. Optimization:
   . Optimizer : Stochastic Gradient Descent(SGD).
   . Hyperparameters:
     . Learning Rate: 0.001
     . Weight Decay: 0.01
3. Training:
   . Number of Epochs: 20
   . Training Loss: 0.1246
   . Training Accuracy: 95.87%
   . Validation Loss: 0.0705
   . Validation Accuracy: 98.47%
4. Inference Testing:
   . Model inference time was evaluated on sample inputs to ensure efficiency.
5. Visualization:
   . Plots of training and validation loss/accuracy trends were generated for detailed performance analysis.

# Results
The fine-tuned MobileNet model demonsterated excellent performance:
. High Validation accuracy of 98.47% indicating strong generalization capabilities.
. Minimal validation loss of 0.0705 confirms the model's robustness.
. Efficient inference time suggests suitability for real-time applications.
   

