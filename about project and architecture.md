This project uses Deep Learning + Transfer Learning to automatically detect whether fruits and vegetables are fresh or rotten from images.

Instead of training a model from scratch, we reuse a pre-trained CNN model (like VGG16 / ResNet / MobileNet) and fine-tune it.
This saves time, data, and gives better accuracy.

 Real-world Uses

Supermarkets & cold storage

Food quality inspection

Smart agriculture systems

Waste reduction in supply chains





Architecture (How the system works)

Flow:

User uploads fruit/vegetable image

Image preprocessing (resize, normalize)

Transfer Learning model (CNN)

Model predicts:

Fresh

Rotten

Result shown in web/app interface


Prerequisites

You need basic knowledge of:

Python

Machine Learning basics

Deep Learning (CNN concept)

Libraries:

TensorFlow / Keras

NumPy

OpenCV

Matplotlib

Flask (for application)