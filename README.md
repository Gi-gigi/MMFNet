# Towards More Accurate and Generalized Tiny Object Tracking: a Large-scale Benchmark and Superior Algorithm

**The code and dataset will be released in the soon.**

***Visiualization video: [Google link](https://drive.google.com/file/d/1sLU90na7nlzqYqsuIhWlTxEBVxKWceJY/view?usp=drive_link)***

***
## Abstract

Despite the significant progress in tiny object tracking algorithms based on convolutional neural networks, the performance falls short of the ideal level due to dataset challenges like small scale, limited scene diversity, low popularity of the competition, and low-resolution (720p) images. The lack of specialized large-scale tiny object tracking datasets leads current algorithms to rely on small and saturated datasets from TrackNet. In this paper, We establish the first comprehensive and high-resolution badminton dataset, named Badminton100K. To our best knowledge, Badminton100K is the first badminton tracking dataset to date that has a high resolution of 1080p. We provide over 100K annotations covering over 200 videos from 12 professional badminton championships. Our dataset covers various badminton events in a broad and diverse background. To enhance the robustness and generalization of tracking algorithms, we also release a high-resolution tennis dataset, Tennis50K, with over 50,000 annotations, and a squash dataset, Squash30K, with over 30,000 annotations. Moreover, considering the fast-moving tiny balls in videos often leads to challenges such as blur, afterimage, overlap, and disappearance. A strong baseline for tiny ball tracking is proposed, a novel cross-stage multi-scale fusion U-shape network (CMU-Net), which can extract local high-resolution details in shallow stages, capture global semantic information in deep stages, and improve context representation through cross-stage and within-stage multi-scale feature fusion, enabling accurate identification and localization of tiny balls. Extensive experiments are conducted on the proposed benchmark datasets, and the results demonstrate that our method achieves unprecedented state-of-the-art tracking performance on Badminton100K, and exhibits outstanding generalization and robustness on Tennis50K and Squash30K.

https://github.com/Gi-gigi/CMU-Net/blob/main/videos/badminton100k.mp4


