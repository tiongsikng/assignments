# assignments
Assignments done throughout Ph. D. course at Yonsei University. Codes may not be perfect according to the description. Reports are available upon request.

### Neural Networks / Special Topics in Deep Learning (NN_STDL)
* `NN_Assignment_1.ipynb` - Drop wave cosine function approximation using linear regression.
* `NN_Assignment_2.ipynb` - Convolutional Neural Networks (CNN) training implementation on CIFAR-10 dataset.
* `NN_Assignment2_1.ipynb` - Transfer learning using CIFAR-10 pretrained model on face dataset. Face dataset is in `face.zip`.
* `NN_Assignment2_2.ipynb` - LSTM implementation to predict bitcoin closing price. The dataset is in `btc.csv`.
* `STDL_Assignment_1.ipynb` - Develop 3 types of customized CNN, namely a normal self-defined CNN, CNN with 1x1 convolution, CNN with depth-wise separable convolution.
* `STDL_Assignment_2.ipynb` - Develop a 1D Generative Adversarial Network (GAN) to generate new datasets, given a set of old datasets. The implementation is based on [this tutorial from this blog](https://machinelearningmastery.com/how-to-develop-a-generative-adversarial-network-for-a-1-dimensional-function-from-scratch-in-keras/).
* `STDL_Assignment2_1.ipynb` - Knowledge Distillation (KD) from a teacher network to a student network. VGG16 is used for the teacher network (using Keras sequential), while the student network is self-defined (as in `STDL_Assignment_1.ipynb`). The distillation class is defined based on [Keras documentation](https://keras.io/examples/vision/knowledge_distillation/). CIFAR-10 is used to train the networks. The distillation works but the results are still not satisfactory.  _(There are future plans to implement a TensorFlow version of this question)_.
* `STDL_Assignment2_2.ipynb` - Implementation of 3 continuous learning methods: Feature Extraction, Fine Tuning, Learning Without Forgetting (LWF), to see performance of the network on old task (CIFAR-10 dataset as in `STDL_Assignment2_1.ipynb`) and new task (face dataset, using `face.zip`). The results are not good, due to implementation issues halfway. _(Future plans to implement a TensorFlow version of this question, similar to `STDL_Assignment2_1.ipynb`)_.

### Digital Image Processing (DIP)
* `Homework_1.ipynb` - Image Discrete Fourier Transform (DFT) in 8x8 blocks, then performing subsampling and interpolation.
* `Homework_2.ipynb` - Discrete Cosine Transform (DCT), Singular Value Decomposition (SVD), Karhunen-Loeve Transform (KLT).
* `Homework_3.ipynb` - Image Differential Pulse Code Modulation (DPCM) and Lloyd-Max Quantization. _(Huffman Coding Part is incomplete)_.
* `Homework_4.ipynb` - Implementation of median filter and FIR filter, specifically using Hamming Window to denoise images with different types of noise.
* `Homework_5.ipynb` - Image Gamma Correction, Histogram Equalization, conversion to YCrCb format.
* `Homework_6.ipynb` - Inverse filter, Wiener filter, constrained matrix inversion filter to deblur cylindrical boundary blurred and Gaussian blurred images.
* `Homework_7.ipynb` - Image segmentation using mean values and Otsu thresholding, object and edge detection using Sobel and Canny filters.

### Random Process (RP)
* `llgc.ipynb` - Implementation of Learning with Local and Global Consistency (LLGC) on two-spirals dataset. The LLGC paper is in [this website](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/LLGC.pdf), while the code implementation is based on [this Git](https://github.com/provezano/lgc).

### Transform Theory (TT)
* `transform_theory.ipynb` - Design a simple self-defined 2-channel filter bank with perfect reconstruction to perform image compression (with 3 level octave filter banks). [PyWavelets](https://pywavelets.readthedocs.io/en/0.2.2/index.html) is used to perform Discrete Wavelet Transform (DWT) of the designed filter on the images to perform the compression.

### Machine Learning 1 (ML)
* `machine_learning.ipynb` - Implement a simple CNN for classification on CIFAR-10 dataset.
