# Unet-for-edema-segmentation

The project is using the U-net for the edema segmentation of fundus images.

Due to the larger workload of images annotation, so I only use a few pictures, and enhance them, simply to test the availability
of the network.

Run:

(1)  python augdata.py
  
(2) sh newtrainnewlabel.sh

(3) python generatenpy.py
  
(4) train your unet:    python unet.py

(5) test your unet , send the test image into unet


The architecture of U-net model:

![image](https://github.com/meteor518/Unet-for-edema-segmentation/blob/master/u-net-model-architecture.png)

The test images are in folder test. The corresponding segmentation results in the folder preds.
