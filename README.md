## Search: "uncertainty quantification object detection autonomous vehicles"

### Link: https://arxiv.org/pdf/2107.04991.pdf
### Year: 2021
### Additional links:

### Abstract:

Object detection in autonomous cars is commonly
based on camera images and Lidar inputs, which are often used
to train prediction models such as deep artificial neural networks
for decision making for object recognition, adjusting speed, etc.
A mistake in such decision making can be damaging; thus, it
is vital to measure the reliability of decisions made by such
prediction models via uncertainty measurement. Uncertainty,
in deep learning models, is often measured for classification
problems. However, deep learning models in autonomous driving
are often multi-output regression models. Hence, we propose a
novel method called PURE (Prediction sURface uncErtainty) for
measuring prediction uncertainty of such regression models. We
formulate the object recognition problem as a regression model
with more than one outputs for finding object locations in a
2-dimensional camera view. For evaluation, we modified three
widely-applied object recognition models (i.e., YoLo, SSD300
and SSD512) and used the KITTI, Stanford Cars, Berkeley
DeepDrive, and NEXET datasets. Results showed the statistically significant negative correlation between prediction surface
uncertainty and prediction accuracy suggesting that uncertainty
significantly impacts the decisions made by autonomous driving.
Index Terms—uncertainty, deep learning, object detection,
autonomous driving

### My notes:

MC dropout based predictions.  
DBSCAN. (convex hull)  
https://prnt.sc/o4eMuT2Pzu6S

-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://link.springer.com/article/10.1007/s42154-021-00154-0
### Year: 2021
### Additional links:

### Abstract:

The safety of the intended functionality (SOTIF) has become one of the hottest topics in the feld of autonomous driving.
However, no testing and evaluating system for SOTIF performance has been proposed yet. Therefore, this paper proposes a
framework based on the advanced You Only Look Once (YOLO) algorithm and the mean Average Precision (mAP) method
to evaluate the object detection performance of the camera under SOTIF-related scenarios. First, a dataset is established,
which contains road images with extreme weather and adverse lighting conditions. Second, the Monte Carlo dropout (MCD)
method is used to analyze the uncertainty of the algorithm and draw the uncertainty region of the predicted bounding box.
Then, the confdence of the algorithm is calibrated based on uncertainty results so that the average confdence after calibration can better refect the real accuracy. The uncertainty results and the calibrated confdence are proposed to be used for
online risk identifcation. Finally, the confusion matrix is extended according to the several possible mistakes that the object
detection algorithm may make, and then the mAP is calculated as an index for ofine evaluation and comparison. This paper
ofers suggestions to apply the MCD method to complex object detection algorithms and to fnd the relationship between
the uncertainty and the confdence of the algorithm. The experimental results verifed by specifc SOTIF scenarios proof the
feasibility and efectiveness of the proposed uncertainty acquisition approach for object detection algorithm, which provides
potential practical implementation chance to address perceptual related SOTIF risk for autonomous vehicles.

### My notes:


-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://kth.diva-portal.org/smash/get/diva2:1618103/FULLTEXT01.pdf
### Year: 2020
### Additional links:

### Abstract:

One of the most challenging problems in autonomous driving, and in computer vision in general, is the task of object detection. Recently, the advances
of deep learning in the domain of computer vision have led the research community to apply ideas from deep learning to the problem of object detection.
Such frameworks have shown promising results by outperforming all of the
traditional approaches based on hand-crafted features. However, deep neural
networks fail to provide reliability measurement for their predictions, which
is a crucial requirement for critical systems. Moreover, it has been shown that
deep neural networks tend to give more overconfident predictions compared
to their shallow counterpart.
Our objective with the current degree project is to review popular deep
neural object detection frameworks and to investigate methods for uncertainty
estimation in deep convolutional neural networks. Additionally, we would like
to find out if applying a method of uncertainty estimation could improve the
performance of a deep neural object detector in terms of standard object detection metrics such as average precision and log average miss rate. Moreover,
we aim at discovering if an approach for measuring reliability improves the
calibration quality of an object detector. Finally, we focus on investigating if
uncertainty estimates could be utilised for detecting misclassified examples or
highly occluded/truncated objects within an image.
In order to answer these questions, we construct a variety of experiments
that investigate different setups and conditions. Overall, we found that uncertainty estimation is a promising approach for alleviating overconfidence in
deep neural networks as well as for providing a reliability measurement for all
predictions.

### My notes:

Monte Carlo dropout to YOLOv3

-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10007375/
### Year: 2023
### Additional links:

### Abstract:

Deep neural network algorithms have achieved impressive performance in object detection.
Real-time evaluation of perception uncertainty from deep neural network algorithms is indispensable
for safe driving in autonomous vehicles. More research is required to determine how to assess the
effectiveness and uncertainty of perception findings in real-time.This paper proposes a novel real-time
evaluation method combining multi-source perception fusion and deep ensemble. The effectiveness
of single-frame perception results is evaluated in real-time. Then, the spatial uncertainty of the
detected objects and influencing factors are analyzed. Finally, the accuracy of spatial uncertainty is
validated with the ground truth in the KITTI dataset. The research results show that the evaluation of
perception effectiveness can reach 92% accuracy, and a positive correlation with the ground truth is
found for both the uncertainty and the error. The spatial uncertainty is related to the distance and
occlusion degree of detected objects

### My notes:

Ansambli

-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://ceur-ws.org/Vol-2640/paper_24.pdf
### Year: 2020
### Additional links:

### Abstract:

A key factor for ensuring safety in Autonomous Vehicles (AVs) is to avoid any abnormal behaviors
under undesirable and unpredicted circumstances.
As AVs increasingly rely on Deep Neural Networks (DNNs) to perform safety-critical tasks, different methods for uncertainty quantification have
recently been proposed to measure the inevitable
source of errors in data and models. However, uncertainty quantification in DNNs is still a challenging task. These methods require a higher computational load, a higher memory footprint, and introduce extra latency, which can be prohibitive in
safety-critical applications. In this paper, we provide a brief and comparative survey of methods for
uncertainty quantification in DNNs along with existing metrics to evaluate uncertainty predictions.
We are particularly interested in understanding the
advantages and downsides of each method for specific AV tasks and types of uncertainty sources.

### My notes:

https://prnt.sc/cO9Va2aFzfGd

-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://library.oapen.org/bitstream/handle/20.500.12657/57375/1/978-3-031-01233-4.pdf BOOK
### Year: 
### Additional links:

### Abstract:


-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://coperception.github.io/double-m-quantification/
### Year: 2023
### Additional links:

### Abstract:

Multiple vehicle collaboration. Not in todays stage of ADAS.

-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://www.iks.fraunhofer.de/content/dam/iks/documents/whitepaper-ml-methods-reliable-perception.pdf BOOK
### Year: 
### Additional links:

### Abstract:


-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://ras.papercept.net/images/temp/IROS/files/0039.pdf
### Year: 2020
### Additional links:

### Abstract:

The capability to detect objects is a core part
of autonomous driving. Due to sensor noise and incomplete
data, perfectly detecting and localizing every object is infeasible.
Therefore, it is important for a detector to provide the amount
of uncertainty in each prediction. Providing the autonomous
system with reliable uncertainties enables the vehicle to react
differently based on the level of uncertainty. Previous work
has estimated the uncertainty in a detection by predicting a
probability distribution over object bounding boxes. In this
work, we propose a method to improve the ability to learn the
probability distribution by considering the potential noise in the
ground-truth labeled data. Our proposed approach improves
not only the accuracy of the learned distribution but also the
object detection performance.

### My notes:

In this work, we improve upon LaserNet [10] which
is a LiDAR-based probabilistic object detector. LaserNet
estimates the uncertainty in its detections by predicting a
probability distribution over bounding boxes for each object.
In the following sections, we will review how the previous
work learns a probability distribution and propose an alternative approach.


https://openaccess.thecvf.com/content_CVPR_2019/papers/Meyer_LaserNet_An_Efficient_Probabilistic_3D_Object_Detector_for_Autonomous_Driving_CVPR_2019_paper.pdf


Experiments show
that modeling each detection as a distribution rather than
a single deterministic box leads to better overall detection
performance. Benchmark results show that this approach
has significantly lower runtime than other recent detectors
and that it achieves state-of-the-art performance when compared on a large dataset that has enough data to overcome
the challenges of training on the range view.


https://prnt.sc/tGsVvEZNo874


-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://mediatum.ub.tum.de/doc/1637914/1637914.pdf
### Year: 2021
### Additional links:

### Abstract:

Estimating the uncertainty of a neural network plays
a fundamental role in safety-critical settings. In perception for
autonomous driving, measuring the uncertainty means providing
additional calibrated information to downstream tasks, such as
path planning, that can use it towards safe navigation. In this
work, we propose a novel sampling-free uncertainty estimation
method for object detection. We call it CertainNet, and it is the
first to provide separate uncertainties for each output signal:
objectness, class, location and size. To achieve this, we propose
an uncertainty-aware heatmap, and exploit the neighboring
bounding boxes provided by the detector at inference time.
We evaluate the detection performance and the quality of the
different uncertainty estimates separately, also with challenging
out-of-domain samples: BDD100K and nuImages with models
trained on KITTI. Additionally, we propose a new metric to
evaluate location and size uncertainties. When transferring to
unseen datasets, CertainNet generalizes substantially better than
previous methods and an ensemble, while being real-time and
providing high quality and comprehensive uncertainty estimates.


https://prnt.sc/2Q4opDf-p7UA


-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link: https://openaccess.thecvf.com/content/ICCV2021/papers/Lu_Geometry_Uncertainty_Projection_Network_for_Monocular_3D_Object_Detection_ICCV_2021_paper.pdf
### Year: 
### Additional links:

### Abstract:


Geometry Projection is a powerful depth estimation
method in monocular 3D object detection. It estimates
depth dependent on heights, which introduces mathematical priors into the deep model. But projection process also
introduces the error amplification problem, in which the error of the estimated height will be amplified and reflected
greatly at the output depth. This property leads to uncontrollable depth inferences and also damages the training efficiency. In this paper, we propose a Geometry Uncertainty
Projection Network (GUP Net) to tackle the error amplification problem at both inference and training stages. Specifically, a GUP module is proposed to obtains the geometryguided uncertainty of the inferred depth, which not only
provides high reliable confidence for each depth but also
benefits depth learning. Furthermore, at the training stage,
we propose a Hierarchical Task Learning strategy to reduce
the instability caused by error amplification. This learning
algorithm monitors the learning situation of each task by a
proposed indicator and adaptively assigns the proper loss
weights for different tasks according to their pre-tasks situation. Based on that, each task starts learning only when
its pre-tasks are learned well, which can significantly improve the stability and efficiency of the training process.
Extensive experiments demonstrate the effectiveness of the
proposed method. The overall model can infer more reliable object depth than existing methods and outperforms
the state-of-the-art image-based monocular 3D detectors by
3.74% and 4.7% AP40 of the car and pedestrian categories
on the KITTI benchmark. The code and model will be released at https://github.com/SuperMHP/GUPNe

### My notes:

Dependent on 3D


-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:


### Link:
### Year: 
### Additional links:

### Abstract:



















































