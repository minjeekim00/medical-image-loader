# Medical Image Loader

This repository was implemented to load DICOM images for [stylegan3](https://github.com/NVlabs/stylegan3) training. </br>
There is no need to prepare datasets using [dataset_tool.py](https://github.com/NVlabs/stylegan3/blob/main/dataset_tool.py). </br>
It will be automatically pre-process and load your DICOM dataset. </br>



## Description

* dataset.py - Official dataset code from stylegan3
* dcm_dataset.py - Revised image folder dataset to load DICOM images
* transform.py - Torchvision-based 16-bit transform functions 
* utils.py - Pre-processing tools 



## Your dataset

Your dataset must be prepared with this tree.

```
directory/
    patient1/
          /00000000000.dcm
          /00000000001.dcm
          /00000000002.dcm
          ...
    patient2/
          /00000000000.dcm
          /00000000001.dcm
          /00000000002.dcm
          ...
    ...
```

or

```
directory/
    /00000000000.dcm
    /00000000001.dcm
    /00000000002.dcm
    /00000000003.dcm
    /00000000004.dcm
    /00000000005.dcm
    ...
```

End with an example of getting some data out of the system or using it for a little demo


