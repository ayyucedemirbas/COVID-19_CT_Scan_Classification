# COVID-19_CT_Scan_Classification

## Abstract

We built and trained a deep learning model to classify CT scan images to COVID and non-COVID. We get almost 93% accuracy for the validation set.


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



![image](https://user-images.githubusercontent.com/8023150/175999135-a07c3759-d1c1-44c5-a1f8-54e3cdf7dd00.png)


![image](https://user-images.githubusercontent.com/8023150/175999182-5ec270f7-a985-4db7-8c0e-07f9b2743710.png)


<img width="635" alt="image" src="https://user-images.githubusercontent.com/8023150/175999243-d7caba5e-7cc1-467c-9b2a-1242af98989e.png">



![image](https://github.com/ayyucedemirbas/COVID-19_CT_Scan_Classification/blob/main/image.png)


