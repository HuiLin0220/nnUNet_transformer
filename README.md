# Usformer: A Small Network for Left Atrium Segmentation of 3D LGE MRI
Mode details are presented in the following papers, [Video](https://www.youtube.com/watch?v=4Mu5rgfUwoE), and [Slides](https://drive.google.com/file/d/1pWzuMKeXzwozWLsFPUuOCRv1JYvT-KXy/view): 

(1) [Usformer: A Light Neural Network for Left Atrium Segmentation of 3D LGE MRI](https://ieeexplore.ieee.org/abstract/document/10289839)

(2) [Usformer: A Small Network for Left Atrium Segmentation of 3D LGE MRI](https://doi.org/10.1016/j.heliyon.2024.e28539)






## Dataset
Median segmentation performance achieved by Usformer
[challenge dataset.](https://ars.els-cdn.com/content/image/1-s2.0-S2405844024045705-mmc1.mp4)
## Instructions
- [Installation instructions]

        git clone https://github.com/HuiLin0220/Usformer.git
        cd Usformer
        pip install -e.
- [Usformer](nnunetv2/dynamic_network_architectures/architectures/unet.py)  Usformer is defined here.
## Oversampling
-oversample_foreground_percent of patches must contain LA
-num_iterations_per_epoch * batch_size * oversample_foreground_percent patches must contain LA

## Example Results
<img align="left" width="252" height="180" src="/results/P20.gif"> A case with median performance in terms of Dice scores in the challenge dataset.

Green lines: prediction
Red lines: groundtruth
Yellow: slice index

Videos for median segmentation performance achieved by Usformer

[challenge dataset](https://ars.els-cdn.com/content/image/1-s2.0-S2405844024045705-mmc1.mp4)
[NU dataset](https://ars.els-cdn.com/content/image/1-s2.0-S2405844024045705-mmc2.mp4)

## References and Acknowledgements:
Usformer is developed on the [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) framework. The  Left Atrium Segmentation project is funded by






## To-do lists
     

