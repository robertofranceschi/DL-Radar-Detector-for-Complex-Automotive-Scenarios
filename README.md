# Deep Learning-Based Radar Detector for Complex Automotive Scenarios

##### Roberto Franceschi, Dmytro Rachkov

![image](https://user-images.githubusercontent.com/57017982/205044534-b099ad35-c7b4-466b-a35c-4795af02018c.png)

Paper: [IEEE Xplore](https://ieeexplore.ieee.org/document/9827045)

## Abstarct
Recent research explored advantages of applying a learning-based method to the radar target detection problem. A single point target case was mainly considered, though. This work extends those studies to complex automotive scenarios. We propose a Convolutional Neural Networks-based model able to detect and locate targets in multi-dimensional space of range, velocity, azimuth, and elevation. Due to the lack of publicly available datasets containing raw radar data (after analog-to-digital converter), we simulated a dataset comprising more than 17000 frames of automotive scenarios and various road objects including (but not limited to) cars, pedestrians, cyclists, trees, and guardrails. The proposed model was trained exclusively on simulated data and its performance was compared to that of conventional radar detection and angle estimation pipeline. In unseen simulated scenarios, our model outperformed the conventional CFAR-based methods, improving by 14.5% the dice score in range-Doppler domain. Our model was also qualitatively evaluated on unseen real-world radar recordings, achieving more detection points per object than the conventional processing.

## Acknowledgment
The authors thank the engineers of Sony Europe B.V., Stuttgart Laboratory 1 for providing the simulator and helpful feedback throughout the work. We thank Prof. Barbara Caputo for the valuable discussions.

## Citation
If you find this project useful in your research, please consider citing:

```
@INPROCEEDINGS{9827045,
  author={Franceschi, Roberto and Rachkov, Dmytro},
  booktitle={2022 IEEE Intelligent Vehicles Symposium (IV)}, 
  title={Deep Learning-Based Radar Detector for Complex Automotive Scenarios}, 
  year={2022},
  volume={},
  number={},
  pages={303-308},
  doi={10.1109/IV51971.2022.9827045}}
```
