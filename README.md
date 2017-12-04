# AutoSweep
This is root folder for all parts of AutoSweep. There are several modules like below:

- AutoSweepMatl
	- **FasterRCNN**: we use deeplab for detection task at first. Finally, we use instances segmentation works.  
	- **Deeplab**: we use deeplab for segementaion task at first. However, we find that this is not suit for instance task.
	- **[PointSetGeneration](https://github.com/fanhqme/PointSetGeneration)**：Code for "A Point Set Generation Network for 3D Object Reconstruction from a Single Image".
	- **[3D-R2N2](https://github.com/chrischoy/3D-R2N2)**:Single/multi view image(s) to voxel reconstruction using a recurrent neural network.
- AutoSweep
	- **FCIS**:we modify [fcis](https://github.com/msracver/FCIS) to be suit for AutoSweep dataset.
	- **MaskRCNN**:we modify [maskrcnn](https://github.com/TuSimple/mx-maskrcnn) to be suit for AutoSweep dataset.
	- **DCN**: Code from [Deformable Deconvolutional Network](https://github.com/msracver/Deformable-ConvNets).
	- **GeonetEnd2End**: This is a attempt for connectting FCIS and DCN.
	- **OneKeyGeonet**: We use this framework based on Matlab, to do experiments and demo.   
	- **AxisClassifier**: The property of curve or straight is estimated by this classifier.
	- **CircleReconstruction**: C++ version of Profile fitting.
	- **AnnatationTool**: The annatiation tool for AutoSweep dataset.
- Unity Part:
	- **ObjectSnap**: Modeling Part of AutoSweep Project based on Unity.