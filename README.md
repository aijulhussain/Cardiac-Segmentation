

This project focused on developing a robust deep learning pipeline for automatic segmentation of the left atrium in cardiac MRI scans. The dataset consisted of 30 3D mono-modal MRI images, from which 110 2D patches of size 
320
×
320
320×320 were extracted using the MedicalTorch framework.

To enhance the model's generalizability, various data augmentation techniques were applied, including center cropping, elastic transformations, random affine transformations, and normalization. A DataLoader with a batch size of 16 was employed for efficient training and validation workflows.

The UNet architecture was chosen for its effectiveness in biomedical image segmentation. Training was conducted over 30 epochs with an initial learning rate of 0.001, dynamically adjusted using a Cosine Annealing Scheduler. To prevent overfitting, early stopping with a patience of 5 epochs was implemented.

The model achieved a training accuracy of 96.12% and a validation accuracy of 93.43%, demonstrating its ability to accurately segment the left atrium. This project highlights proficiency in medical image preprocessing, data augmentation, and deep learning model optimization for clinical applications.

Dataset link: https://drive.google.com/file/d/1wEB2I6S6tQBVEPxir8cA5kFB8gTQadYY/view?usp=drive_link
