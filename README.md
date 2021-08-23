# Transfer learning using Keras with DenseNet-169

The DenseNet 169 model architectures for ImageNet,

![1_RUiMzddMbQ0rx_CCqT2k8Q](https://user-images.githubusercontent.com/84494071/130454804-3dcd7728-59cc-4ded-84c4-c6b2d3b72a88.png)

#Referance:
https://arxiv.org/pdf/1608.06993.pdf

# Data:
Here i am using flower recognition data from kaggle, This is the link you can download from there https://www.kaggle.com/alxmamaev/flowers-recognition

# Steps:
1. Downloading the data, upload that into my drive and setting the path.
2. Visualize the data
3. Split folders into train,test and valid.
4. performing data augmentaion.
5. Download the DenseNet-169 model from keras application.
6. After that i built my architecture,called pretrained model,then created two more dense layer.
7. Compiling my model with loss function,optimizer and metrics.
8. After that i started training for 2 epochs.results are shown below,
 
![ree](https://user-images.githubusercontent.com/84494071/130457348-49cd705c-7a6a-4c24-95a2-2eda44d5bfab.JPG)


