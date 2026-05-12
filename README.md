# GCN_DAL
This repo contains the codes for our manuscript "Graph Refactored Domain Adversarial Learning for Underwater Image Enhancement". The code will be opensourced after acceptance of the paper.

Step 0: Create the enviornmnet using env.yml file.

Step 1: The dataset is prepared first by running data_prep.py which will degrade the images in raw folder as per the degradation coefficients and clear images are placed in the ref folder.

Step 2: The data to train and test the model is present in the data folder. The raw degraded images and enhanced images are present for all the classes. Each class has 890 images. label_train and label_test.csv tells the dataloader which are train images and which are test images.

Step 3: Train the model by running main.py

Step 4: Run the inference by running test.py


The structure of this repo is as follows:

-data_prep
|-prep.py
|-ref_images


-data
|--raw
|---0
|---1
|---2
|---3
|---4
|---5
|--ref
|---0
|---1
|---2
|---3
|---4
|---5
|--label_train.csv
|--label_test.csv

-main.py
-test.py
-env.yml

