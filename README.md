# mmseg
The datasets used in my previous tests can be found in "/mmsegmentation/data" directory. In details:

-CHASE_DB1 is a dataset gievn by mmsegmentation

-LARS is the dataset used by Luca for macvi challenge

-z is the dataset containing all the images and masks of ISBI according to lars.py

-z1 is the dataset containing a subset of ISBI data according to lars.py

-z2 is the dataset containing a subset of ISBI data without images that are entirely black according to chase_db1.py

-z3 is the dataset containing only the middle slice of each mri image accordining to chase_db1.py

-z4 is the dataset containing all the imagees and masks of MSL according to MSL.py

pls be careful before start the training, once it was not working, all files were returned to the initial condition.

only "python tools/train.py configs/unet/unet-s5-d16_pspnet_4xb4-ce-1.0-dice-3.0-40k_msl-128x128.py" works as it was the last test started with the z4 dataset.
