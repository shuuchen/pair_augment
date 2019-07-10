# pair_augment
image and label pair augmentation for computer vision projects

## problems of data augmentation
In semantic segmentation, image-label pairs should be augmented equally. Sometimes, data augmentation fails due to the following issues:
- Augmented data is out of domain. (for logos etc.)
- Distribution of augmented data is different. (for dtype conversion etc.)

## compare train/valid loss curve to check overfitting
If data augmentation succeeds, the valid loss curve will converge to train loss curve, otherwise they will fall apart at early stage of training.
