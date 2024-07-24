# Project abstract
Semantic segmentation is a key technique in computer vision that enables the identification of specific objects within images and is a crucial task across various applications, from medical imaging to autonomous driving. Our focus is on comparing the performance of several deep learning models on the Oxford IIIT Pet Dataset. Apart from fine-tuning the FCN-ResNet50  and the DeepLabV3-ResNet50, we implemented some instances of the DenseASPP and a simple architectural variation of it. Having this set of network designs and varying the datasets on which the models were trained allowed us to evaluate which transfer learning approach works best for our specific task. Our best model, an instance of DenseASPP, obtained a pixel accuracy of 92\% and a weighted mIoU of 85\% on the test set. Additionally, we performed a qualitative assessment of the models' predictions, taking into account their key characteristics, the way they were trained, and the challenges they faced.

## Repository description
- A PDF report with the complete explanation of what was done.
- The Jupyter Notebook with the full implementation.

This was the final project for the [Vision and Cognitive Systems](https://en.didattica.unipd.it/off/2022/LM/SC/SC2377/001PD/SCQ1097939/N0) course of my master's degree.
