# COVID-19_CT_Scan_Classification

## Abstract

We built a deep learning model to classify CT scan images to COVID and non-COVID. The training accuracy is around 91%.


![image](https://github.com/ayyucedemirbas/COVID-19_CT_Scan_Classification/blob/main/image.png)




               Model: "sequential"
                _________________________________________________________________
                Layer (type)                 Output Shape              Param #   
                =================================================================
                rescaling (Rescaling)        (None, 255, 255, 3)       0         
                _________________________________________________________________
                conv_1 (Conv2D)              (None, 255, 255, 64)      1792      
                _________________________________________________________________
                conv_2 (Conv2D)              (None, 255, 255, 8)       4616      
                _________________________________________________________________
                pool_1 (MaxPooling2D)        (None, 31, 31, 8)         0         
                _________________________________________________________________
                conv_3 (Conv2D)              (None, 31, 31, 16)        1168      
                _________________________________________________________________
                flatten (Flatten)            (None, 15376)             0         
                _________________________________________________________________
                dense_1 (Dense)              (None, 16)                246032    
                _________________________________________________________________
                dense_2 (Dense)              (None, 2)                 34        
                =================================================================
                Total params: 253,642
                Trainable params: 253,642
                Non-trainable params: 0
                _________________________________________________________________


