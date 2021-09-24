# Data Augmentation using DCGANs for Covid-19 detection in X-Ray images
In this Project we apply and assess data augmentation via Generative Adversarial Neural Networks (GANs) to X-Ray images of lungs who were classified either as Covid-19 positive or negative. 
To study the efficiency of data augmentation in this case, we used a deep Convolutional Neural Network (CNN) to classify the  images.

The directory structure for the data is done in the following way:
    .
    ├── datasets                   
    |   ├── <dataset_name>         # i.e. brucewayne2batman
    |   |   ├── train              # Training
    |   |   |   ├── A              # Contains domain A images (i.e. Bruce Wayne)
    |   |   |   └── B              # Contains domain B images (i.e. Batman)
    |   |   └── test               # Testing
    |   |   |   ├── A              # Contains domain A images (i.e. Bruce Wayne)
    |   |   |   └── B              # Contains domain B images (i.e. Batman)
