<!--# Towards More Accurate Tiny Object Tracking: Benchmark and Algorithm-->
# Towards More Accurate Tiny Object Tracking: Benchmark and Algorithm

### Note: The Code will be released in the soon.

***The datasets are available at [Badminton100K](https://drive.google.com/file/d/1UM8Lg7fzoQK822b2itSl-p1gWvTDfBvB/view?usp=sharing) (Sample)***

***

### More comprehensive Visulaization Results.
***More comprehensive visual videos are accessible: [Videos](https://drive.google.com/file/d/1cct8fJKL2N9hG3lXMfDmsFQ7Q_xsSn7R/view?usp=sharing)***

https://github.com/Gi-gigi/CMU-Net/assets/49682456/6803629d-7715-4d2f-ba7a-621e84cbce58

https://github.com/Gi-gigi/MMFNet/assets/49682456/17923b84-f46f-477b-a18a-9b996029c429

https://github.com/Gi-gigi/MMFNet/assets/49682456/fc76d859-a7ea-4921-9273-baba44aac5a9

https://github.com/Gi-gigi/MMFNet/assets/49682456/698f0267-bc1b-4170-8e52-a7a36be4fddc

***

### Abstract
Despite the significant progress in tiny object tracking algorithms based on convolutional neural networks, the performance falls short of the ideal level due to dataset challenges like limited scale, limited match backdrop, low match popularity, and low-resolution(720p) images. The lack of specialized large-scale tiny object tracking datasets leads data-hungry tracking algorithms to rely on small and saturated datasets from TrackNet.  This paper propels the development of tiny object tracking and contributes the first large-scale dataset, Badminton100K, for tiny ball tracking.  We provide over 100K annotations covering over 200 videos from 12 professional match events.  Our dataset covers high-resolution(1080p) match videos in broad and diverse contexts. Moreover, considering the fast-moving tiny balls in videos often leads to challenges such as blur, afterimage, overlap, and disappearance. As another contribution, we also propose a novel Multi-stage and Multi-scale Fusion Network (MMFNet), which can extract local high-resolution details in the shallow stages and capture global semantic information in the deep stages, addressing these challenging tasks through multiple stages multi-scale feature fusion, enabling accurate identification and localization of tiny balls.  Extensive experiments show that our method achieves unprecedented state-of-the-art tracking performance on Badminton100K.

***

### Experiments

|             | MMFNet(MISO) |    MMFNet(SISO)  | 
| :----:      |     :----:   |      :----:      | 
|    ACC      |       96.91%       |         90.02%         |
|    PRE      |       98.67%       |         96.33%         |
|    REC      |       97.85%       |         92.44%         |


