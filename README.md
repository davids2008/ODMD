# ODMD (more updates soon!)
ODMD is the first dataset for learning **O**bject **D**epth via **M**otion and **D**detection. ODMD training data are configurable and extensible, with each training example consisting of a series of object detection bounding boxes, camera movement distances, and ground truth object depth. As a benchmark evaluation, we provide four ODMD validation and test sets with 21,600 examples in multiple domains, and we also convert 15,650 examples from the [ODMS benchmark](https://github.com/griffbr/odms) for detection. In our paper, we use a single ODMD-trained network with object detection *or* segmentation to achieve state-of-the-art results on existing driving and robotics benchmarks and estimate object depth from a camera phone, demonstrating how ODMD is a viable tool for monocular depth estimation in a variety of mobile applications.

Contact: Brent Griffin (griffb at umich dot edu)

__Depth Results using a Camera Phone.__
![alt text](https://github.com/griffbr/ODMD/blob/master/figure/example_ODMD_phone_results.jpg "Depth Results using a Camera Phone")

## Publication
Please cite our paper if you find it useful for your research.
```
@inproceedings{GrCoCVPR21,
  author = {Griffin, Brent A. and Corso, Jason J.},
  booktitle={The European Conference on Computer Vision (CVPR)},
  title = {Depth from Camera Motion and Object Detection},
  year = {2021}
}
```

## Use

This code is available for non-commercial research purposes only.