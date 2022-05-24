# Medical Image Loader

This repository was implemented to load DICOM images for [stylegan3](https://github.com/NVlabs/stylegan3) training.
There is no need to prepare datasets using [dataset_tool.py](https://github.com/NVlabs/stylegan3/blob/main/dataset_tool.py).
It will be automatically pre-process and load your DICOM dataset.


## Short Description for each file

* dataset.py - Official dataset code from stylegan3
* dcm_dataset.py - Revised ImageFolder dataset to load DICOM images
* transform.py - Torchvision-based 16-bit transform functions 
* utils.py - Pre-processing tools 
