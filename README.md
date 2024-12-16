# classification-model-with-residual-and-inception-block-
the image classification model uses residual block and inception model， integrates deep wise convolution and attention mechanism
# This notebook is a six-class image classification for solar panels
# Below are some comments for this notebook
1. metrics
   this notebook uses 8 metrics: Accuracy、Precision、Recall、F1-Score、Specificity、ROC-AUC、Top-k Accuracy、Logarithmic Loss (Log Loss)      and confusion matrix
2. model
   The model will combine:(1)Residual Learning: Add skip connections to mitigate vanishing gradients.(2)Inception Module:Use filters of       varying sizes (1x1, 3x3, 5x5) and a bottleneck strategy to reduce parameters.(3)Depthwise Separable Convolutions: Efficient convolution    operations to reduce computational load.(4)Attention Mechanism:Implement a channel attention mechanism like Squeeze-and-Excitation        (SE) blocks.
3. XAI
   this notebook uses GradCAM for XAI
