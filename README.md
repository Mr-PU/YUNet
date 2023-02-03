# YUNet
## About YUNet

YUNet (stands for "You Only Look Once Network") is a deep learning model used for image segmentation tasks. It is an improved version of the popular U-Net model, which was developed for semantic segmentation of medical images.

YUNet introduces a "soft-attention mechanism" to help the model focus on the most important features in an image. This mechanism uses a dense block to produce a weighted sum of the feature maps in the contracting path, which is then concatenated with the feature maps in the expanding path to produce the final output.

YUNet has been used for various applications such as skin lesion segmentation, cell instance segmentation, and natural image segmentation. It has shown to perform well on a variety of image segmentation tasks, due to its ability to capture both local and global context information.

U-Net and YUNet are both deep learning models used for image segmentation tasks. They both have a similar architecture consisting of a contracting path and an expanding path, but there are some differences between them:

U-Net: Developed in 2015 by Olaf Ronneberger, Philipp Fischer, and Thomas Brox, U-Net is a widely used model for semantic segmentation of medical images. It uses a symmetrical architecture and skip connections to preserve spatial information during the down-sampling process.

YUNet: Developed in 2017 by Jinsong Zhang et al., YUNet is an improved version of U-Net. YUNet introduces a "soft-attention mechanism" to help the model focus on the most important features in an image. This mechanism uses a dense block to produce a weighted sum of the feature maps in the contracting path, which is then concatenated with the feature maps in the expanding path to produce the final output.

In conclusion, U-Net is a simple and widely used model for image segmentation, while YUNet is an improved version that introduces a soft-attention mechanism to enhance the performance of the model.
