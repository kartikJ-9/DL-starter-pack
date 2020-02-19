Face Recognition is also implemented using ResNet.
ResNet is similar to Google's LeNet.

ResNet Model:
7x7 Convolutional Layer
64 Output channel
Stride of 2
3x3 Maxpool Layer
Stride of 2
Batch normalization layer added after each convolutional layer

The prototxt file contains the architecture of the model.
caffemodel file contains the weights for the Neural Network to learn.

Performance:
It is computationally heavy for microprocessors like Raspberry Pi. Hence, if the application requires deployment of face recognition module in microprocesors.
On the other side, it is more accurate than the Haar Cascade. This ResNet Model is already in the OpenCV package.

Reference:
Pyimagesearch
sentdex -> YouTube
