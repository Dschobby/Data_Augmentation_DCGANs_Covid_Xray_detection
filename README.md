# Data Augmentation using DCGANs for Covid-19 detection in X-Ray images
In this Project we apply and assess data augmentation via Generative Adversarial Neural Networks (GANs) to X-Ray images of lungs who were classified either as Covid-19 positive or negative. 
To study the efficiency of data augmentation in this case, we used a deep Convolutional Neural Network (CNN) to classify the  images.

The directory structure for the data is done in the following way:

    ├── data                   
    |   ├── COVID_data                   
    |   |   ├── COVID                    # Training Covid positive images
    |   ├── COVID_data_GENERATED         
    |   |   ├── GENERATED                # Generated Covid positive images from GAN
    |   ├── COVID_data_TEST              
    |   |   ├── TEST                     # Test Covid positive images
    |   ├── Normal_data                  
    |   |   ├── Normal                   # Training Covid negative images
    |   ├── Norma_data_GENERATED         
    |   |   ├── GENERATED                # Generated Covid negative images from GAN
    |   ├── Normal_data_TEST             
    |   |   ├── TEST                     # Test Covid negative images
    
