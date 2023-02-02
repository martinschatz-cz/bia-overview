# BiA Approaches

## My Tested tools
To be filled in soon.

- [x] YOLOv5 - SciCount
- [x] ImageJ in Python
- [x] pyimg - Image quality assesment
- [ ] StarDist
- [ ] Noise2Void
- [ ] CellPose
- [ ] PhyCV - physics-inspired Computer Vision Library

### [YOLOv5 - SciCount](https://github.com/martinschatz-cz/SciCount)
SciCount is tool focused on counting and classifying of objects in image-like data and scientific images, with training and example datasets. In it core it is YOLO V5 made by [Ultralytics](https://github.com/ultralytics/yolov5) (authored by [Glenn Jocher](https://www.linkedin.com/in/glenn-jocher/)), without which it would be impossible to apply our approaches on scientific data.

You can find example notebooks aplying reproducible augmentatioin [SciAugment](https://github.com/martinschatz-cz/SciAugment) with small test datasets in folder example_notebooks. There is reproducible example for **LTEE**, **Wildlife detection** and **Smear counting**.

### [PyImageJ - ImageJ in Python](https://github.com/martinschatz-cz/pyimagej-julab)
Running ImageJ and its macros through Python, in local Jupyter Hub. Tested on 3 computers.

### [pyimq](https://github.com/martinschatz-cz/image_quality_assesment)
A quite impressive package for image quality assesment, tested on 3 images provided by the creators. 
 
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
