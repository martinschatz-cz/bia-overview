# BiA Approaches

## My Tested tools
To be filled in soon.

- [x] YOLOv5 - SciCount
- [x] ImageJ in Python
- [x] pyimg - Image quality assessment
- [x] StarDist
- [x] Noise2Void
- [x] CellPose
     - [x] CellPose 2.0
     - [x] CellPose custom models
- [ ] PhyCV - physics-inspired Computer Vision Library

### CellPose
With the CellPose 2.0 came an option to fine-tune the models, which opens up a lot of possibilities. With a direct connection to FIJI and Trackmate with [trackMate-Cellpose](https://imagej.net/plugins/trackmate/detectors/trackmate-cellpose), it is possible now to track the time-lapses and more. We can look forward to more files covering that, but for now, I at least created a simple [Visual Cheat Sheet](https://doi.org/10.6084/m9.figshare.24441214.v1) to help tackle some of the usage during my lectures.

### Noise2Void
Noise2Void (N2V) is a powerful, context aware and flexible algorithm for image denoising. It uses artificial neural networks to learn about the properties of your images and how to best denoise them. N2V outperforms traditional denoising techniques. A tutorial for FIJI with files, presentations and more can be found in the [https://zenodo.org/record/8025067](BioImage Analysis and Superresolution Microscopy Workshop 2023 (at Dartmouth College)) Zenodo repository of [https://web.natur.cuni.cz/sekce-bi/VMCF/worskhops/](BioImage Analysis and Superresolution Microscopy Workshop 2023).

### StarDist
StarDist is a fantastic, deep-learning-based method of 2D and 3D nucleus detection from Martin Weigert and Uwe Schmidt. It exists as a Python library and Fiji plugin.

#### FIJI
A tutorial with files, presentations and more can be found in the [https://zenodo.org/record/8025067](BioImage Analysis and Superresolution Microscopy Workshop 2023 (at Dartmouth College)) Zenodo repository of [https://web.natur.cuni.cz/sekce-bi/VMCF/worskhops/](BioImage Analysis and Superresolution Microscopy Workshop 2023).

#### QuPath
[Here](https://www.youtube.com/watch?v=UI_Sfv3rNo4&list=PLZSnRdb-MTNfBx6Q8wKbu-5oyAo0FttCE&index=2&ab_channel=MarkZaidi) is a very nic YouTube video explaining how to use StarDist models in QuPath. The general models are available from [Universal-StarDist-for-QuPath](https://github.com/MarkZaidi/Universal-StarDist-for-QuPath) GitHub. You can find more info and scripts in [this](https://github.com/vmcf-konfmi/QuPath) GitHub repository.

### [YOLOv5 - SciCount](https://github.com/martinschatz-cz/SciCount)
SciCount is tool focused on counting and classifying of objects in image-like data and scientific images, with training and example datasets. In it core it is YOLO V5 made by [Ultralytics](https://github.com/ultralytics/yolov5) (authored by [Glenn Jocher](https://www.linkedin.com/in/glenn-jocher/)), without which it would be impossible to apply our approaches on scientific data.

You can find example notebooks aplying reproducible augmentatioin [SciAugment](https://github.com/martinschatz-cz/SciAugment) with small test datasets in folder example_notebooks. There is reproducible example for **LTEE**, **Wildlife detection** and **Smear counting**.

### [PyImageJ - ImageJ in Python](https://github.com/martinschatz-cz/pyimagej-julab)
Running ImageJ and its macros through Python, in local Jupyter Hub. Tested on 3 computers.

### [pyimq](https://github.com/martinschatz-cz/image_quality_assesment)
A quite impressive package for image quality assesment, tested on 3 images provided by the creators. 

### [Other tool tests](https://github.com/martinschatz-cz/tool_tests)
This package contains various test of packages and logs of how I installed them. The aim is to use Jupyter Lab, but the tools also have GUI.

#### [pyTFM](https://github.com/martinschatz-cz/tool_tests/tree/main/pyTFM)
pyTFM is a python package that allows you to analyze force generation and stresses in cell colonies and confluent cell layers growing on a 2 dimensional surface. This package implements the procedures of Traction Force Microscopy and Monolayer Stress Microscopy.

#### [Cell ACDC](https://github.com/martinschatz-cz/tool_tests/tree/main/Cell_ACDC)
A GUI-based Python framework for segmentation, tracking, cell cycle annotations and quantification of microscopy data.
 
## Wish List

### YOLOv8
YOLOv8 is the latest version of the YOLO (You Only Look Once) object detection and image segmentation model developed by Ultralytics. This notebook serves as the starting point for exploring the various resources available to help you get started with YOLOv8 and understand its features and capabilities.

The YOLOv8 models are designed to be fast, accurate, and easy to use, making them an excellent choice for a wide range of object detection and image segmentation tasks. They can be trained on large datasets and are capable of running on a variety of hardware platforms, from CPUs to GPUs.

 * [Tutorial](https://github.com/ultralytics/ultralytics/blob/main/examples/tutorial.ipynb)
 
### PhyCV - The First Physics-inspired Computer Vision Python library

PhyCV is a Physics-inspired Computer Vision Python library. PhyCV has a new class of computer vision algorithms that emulates the propagation of light through a physical medium with natural and engineered diffractive properties followed by coherent detection. Unlike traditional algorithms that are a sequence of hand-crafted empirical rules, physics-inspired algorithms leverage physical laws of nature as blueprints. These algorithms can, in principle, be implemented in real physical devices for fast and efficient computation. Currently, PhyCV includes Phase-Stretch Transform (PST), Phase-Stretch Adaptive Gradient-field Extractor (PAGE) and Vision Enhancement via Virtual diffraction and coherent Detection (VEViD). Each algorthm has CPU and GPU versions.

#### Phase-Stretch Transform (PST)
Phase Stretch Transform (PST) is a computationally efficient edge and texture detection algorithm with exceptional performance in visually impaired images. Inspired by the physics of the photonic time stretch.

#### Phase-Stretch Adaptive Gradient-field Extractor (PAGE)
Phase-Stretch Adaptive Gradient-field Extractor (PAGE) is a physics-inspired algorithm for detecting edges and their orientations in digital images at various scales. The algorithm is based on the diffraction equations of optics. Metaphorically speaking, PAGE emulates the physics of birefringent (orientation-dependent) diffractive propagation through a physical device with a specific diffractive structure.

#### Vision Enhancement via Virtual diffraction and coherent Detection (VEViD)
Similar to PST and PAGE, VEViD a efficient and interpretable low-light and color enhancement algorithm that reimagines a digital image as a spatially varying metaphoric light field and then subjects the field to the physical processes akin to diffraction and coherent detection. The term “Virtual” captures the deviation from the physical world. The light field is pixelated and the propagation imparts a phase with an arbitrary dependence on frequency which can be different from the quadratic behavior of physical diffraction. 

 * [GitHub](https://github.com/JalaliLabUCLA/phycv)
