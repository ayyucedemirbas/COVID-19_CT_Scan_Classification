# COVID-19_CT_Scan_Classification

## Abstract

We built and trained a deep learning model to classify CT scan images to COVID and non-COVID. We get 94% accuracy for the test set.

Please do not try to work on this project. It was a fucking school assignment and they only provided almost 2000 images and asked us to train a model from completely scratch. So models tend to overfit because of insufficient data.


    Model: "model"
    _________________________________________________________________
     Layer (type)                Output Shape              Param #   
    =================================================================
     input_1 (InputLayer)        [(None, 255, 255, 3)]     0         

     rescaling (Rescaling)       (None, 255, 255, 3)       0         

     conv2d (Conv2D)             (None, 255, 255, 128)     3584      

     conv2d_1 (Conv2D)           (None, 255, 255, 128)     147584    

     max_pooling2d (MaxPooling2D  (None, 127, 127, 128)    0         
     )                                                               

     dropout (Dropout)           (None, 127, 127, 128)     0         

     conv2d_2 (Conv2D)           (None, 127, 127, 64)      73792     

     conv2d_3 (Conv2D)           (None, 127, 127, 64)      36928     

     max_pooling2d_1 (MaxPooling  (None, 63, 63, 64)       0         
     2D)                                                             

     dropout_1 (Dropout)         (None, 63, 63, 64)        0         

     conv2d_4 (Conv2D)           (None, 63, 63, 32)        18464     

     conv2d_5 (Conv2D)           (None, 63, 63, 32)        9248      

     max_pooling2d_2 (MaxPooling  (None, 31, 31, 32)       0         
     2D)                                                             

     dropout_2 (Dropout)         (None, 31, 31, 32)        0         

     conv2d_6 (Conv2D)           (None, 31, 31, 16)        4624      

     conv2d_7 (Conv2D)           (None, 31, 31, 16)        2320      

     max_pooling2d_3 (MaxPooling  (None, 15, 15, 16)       0         
     2D)                                                             

     dropout_3 (Dropout)         (None, 15, 15, 16)        0         

     flatten (Flatten)           (None, 3600)              0         

     dense (Dense)               (None, 8)                 28808     

     dense_1 (Dense)             (None, 1)                 9         

    =================================================================
    Total params: 325,361
    Trainable params: 325,361
    Non-trainable params: 0
    _________________________________________________________________



![model](https://user-images.githubusercontent.com/8023150/175999977-03c0ec0c-bef5-44a4-9d02-6bfd7b6d97ac.png)



<img width="384" alt="Screen Shot 2022-09-28 at 05 11 13" src="https://user-images.githubusercontent.com/8023150/192672202-e130460f-cb10-4f42-a4b7-cedca8dae418.png">


<img width="384" alt="Screen Shot 2022-09-28 at 05 11 03" src="https://user-images.githubusercontent.com/8023150/192672177-24ab0fdf-4390-40cf-9400-96ba70052df7.png">


<img width="651" alt="image" src="https://user-images.githubusercontent.com/8023150/192672313-ec5fc346-7469-492b-a14d-f55a6148fe72.png">



![image](https://github.com/ayyucedemirbas/COVID-19_CT_Scan_Classification/blob/main/image.png)


