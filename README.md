# Super resolution undersampled MRI


### File description

`modl_training_pipeline.ipynb` : MoDL network for training and testing low resolution undersampled MRI to dealiased and denoised low resolution

`GAN superresolution Phase 2.ipynb` : SR Resnet model for training and testing low resolution MRI to high resolution

Link for the dataset to run MoDL: https://iowa-my.sharepoint.com/:f:/g/personal/moalam_uiowa_edu/EtTkM9rA1TtApSuhJ96eJTEBVY6je8vuf4elCQBLCiqVRQ?e=VxrHrO

*How to run the code*

Step 1 : Setup the enviornment for the MoDL (MoDL.yml)
Step 2 : Run the modl training pipeline with essential dataset
Step 3 : Extract MoDL output and save it as a file folder
Step 4 : Setup envioronment for the SRResnet ( SRResEnv.yml)
Step 5 : Run the Gan superreolution phase 2 notebook for training and testing the images.


*Our code is based on the following research articles*

1. Xu, Yang, et al. "Hyperspectral images super-resolution via learning high-order coupled tensor ring representation." IEEE transactions on neural networks and learning systems 31.11 (2020): 4747-4760.
2. Chen, Yuhua, et al. "Brain MRI super resolution using 3D deep densely connected neural networks." 2018 IEEE 15th International Symposium on Biomedical Imaging (ISBI 2018). IEEE, 2018.
3. Köhler, Thomas. "Multi-frame super-resolution reconstruction with applications to medical imaging." arXiv preprint arXiv:1812.09375 (2018).
4. Basty, Nicolas, and Vicente Grau. "Super resolution of cardiac cine MRI sequences using deep learning." Image Analysis for Moving Organ, Breast, and Thoracic Images. Springer, Cham, 2018. 23-31.
5. Huang, Yawen, Ling Shao, and Alejandro F. Frangi. "Simultaneous super-resolution and cross-modality synthesis in magnetic resonance imaging." Deep Learning and Convolutional Neural Networks for Medical Imaging and Clinical Informatics. Springer, Cham, 2019. 437-457.
6. Zhang, Lei, et al. "Exploiting clustering manifold structure for hyperspectral imagery super-resolution." IEEE Transactions on Image Processing 27.12 (2018): 5969-5982.
7. K. Ren, Y. Yang and L. Meng, "Single image super-resolution reconstruction via combination mapping with sparse coding," 2017 International Conference on Progress in Informatics and Computing (PIC), 2017, pp. 200-204, doi: 10.1109/PIC.2017.8359542.
8. Tong, Tong, et al. "Image super-resolution using dense skip connections." Proceedings of the IEEE international conference on computer vision. 2017.
9. C. Dong, C. C. Loy, K. He and X. Tang, "Image Super-Resolution Using Deep Convolutional Networks," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 38, no. 2, pp. 295-307, 1 Feb. 2016, doi: 10.1109/TPAMI.2015.2439281.
10. Shi, W., Caballero, J., Huszár, F., Totz, J., Aitken, A. P., Bishop, R., ... & Wang, Z. (2016). Real-time single image and video super-resolution using an efficient sub-pixel convolutional neural network. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 1874-1883).
11. Pham, Chi-Hieu, et al. "Multiscale brain MRI super-resolution using deep 3D convolutional networks." Computerized Medical Imaging and Graphics 77 (2019): 101647.
12. Ledig, Christian, et al. "Photo-realistic single image super-resolution using a generative adversarial network." Proceedings of the IEEE conference on computer vision and pattern recognition. 2017.
13. Chen, Yuhua, et al. "Efficient and accurate MRI super-resolution using a generative adversarial network and 3D multi-level densely connected network." International Conference on Medical Image Computing and Computer-Assisted Intervention. Springer, Cham, 2018.
14. Aggarwal, Hemant K., Merry P. Mani, and Mathews Jacob. "MoDL: Model-based deep learning architecture for inverse problems." IEEE transactions on medical imaging 38.2 (2018): 394-405.
