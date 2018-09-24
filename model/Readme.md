This folder contains the files related to training the model. Go to the 'data' and 'model_data' folder and dowdnload the respective files there. 

- Train Model - YOLOv2.ipynb : Contains the code for training the model using the YOLO algorithm and then testing it on real time video. 
- Preprocess image and boxes.ipynb : Contains the code to preprocess the images and box coordinate files and save them a .npy array files.
- data : This folder contains the preprocessed saved .npy files and the ouput files after running the model on test data.
- model_data : This folder stores the pre-trained model weights required for training.
- logs : This folder maintains the logs while training the model.
- YAD2K : This folder contains files to convert the darknet model to keras. YAD2K files are taken from the git repo of Allan Zelener. You can check out the [original YAD2K repository](https://github.com/allanzelener/YAD2K) here. 
