# SAR Target Classification using Deep Learning
This project is done by me and Ratikant Patil under supervision of Dr. Hanumant Singh Shekawat for my thesis project that should be submitted by May 2019. This repository doesn't contain any code, to avoid plagiarism.

## Abstract
Synthetic aperture radar (SAR) is an imaging radar that produces high-resolution images. Classifying targets that are detected within a SAR image find many applications in environment monitoring and mapping. In this project an approach is proposed to classify targets that are detected in a SAR image. In this approach, dataset is passed through CNN to automatically extract features. These feature vectors are then passed to softmax classifier for its training. Examinations on the general MSTAR informational collection demonstrates that an exactness of 99% can be accomplished when classification is done on two kinds of targets, and a precision of 98% on seven sorts of targets.

## Conclusion
As a initial study, three layers of CNN have been applied to the SAR data set, as feature extractors
and pooling has been done. A simple softmax classifier is used to achieve an exactness
of 99% for two kinds of targets and 98% for seven distinct targets. Simple data augmentation
technique has been implemented due to the scarcity of SAR image samples. Regularization
technique has been used to avoid overfitting.

##Future Work
It can be seen that simple CNN used in this approach can classify SAR image targets with an
accuracy of 98% but to make this model more robust, tests have to be made at different depression
angles and different kinds of SAR Imagery targets. Instead of augmentation, Transfer
learning approach can be applied to obtain better classification with small amounts of data. In
this approach, multiple pre-trained classifiers are used to extract useful features, along with a
classifier.
