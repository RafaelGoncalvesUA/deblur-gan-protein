# Generative Image Deblurring for Human Protein Cell Classification
Microscope images often suffer from motion blur, due to long exposure times or camera shake, compromising the success of computer vision tasks, such as image segmentation and classification. In this work, we address the problem of image deblurring by leveraging a dataset from the Human Protein Atlas (HPA), a project that aims to find protein organelles in human cells.

We first simulate motion blur in the spatial domain through kernel convolution and then implement three Deep Learning methods: a Deep Convolutional AutoEncoder (DCAE) and a Generative Adversarial Network (GAN) - both from scratch, as well as the fine-tuning of MAXIM, a pre-trained deblurring model from Google Research. A simple Wiener filter is also applied as a baseline.

We then evaluate and compare the performance of the proposed solutions based on two well-known image quality metrics: Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index (SSIM). Finally, we validate our models by feeding a publicly available protein image classifier with our predicted images.

**Result**: the developed methods can effectively deblur the images and improve the classifier’s F1 score by at most 226.5%.

----

**FULL REPORT**: [report.pdf](report.pdf)
