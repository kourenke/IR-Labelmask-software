# IR-Labelmask-software

@ARTICLE{10506340,

  author={Kou, Renke and Wang, Chunping and Fu, Qiang and Li, Zhanwu and Luo, Ying and Li, Boyang and Li, Wei and Peng, Zhenming},
  
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  
  title={MCGC: A Multiscale Chain Growth Clustering Algorithm for Generating Infrared Small Target Mask Under Single-Point Supervision}, 
  
  year={2024},
  
  volume={62},
  
  number={},
  
  pages={1-12},
  
  keywords={Annotations;Clustering algorithms;Software algorithms;Shape;Task analysis;Software;Training;Euclidean coefficient attenuation;infrared (IR) small target;mask annotation software;multiscale chain;pseudo mask generation;single-point supervision},
  
  doi={10.1109/TGRS.2024.3390756}}

Abstract—Due to the lack of color and texture information and the fuzzy boundary of infrared (IR) small targets, the pixel-level mask annotation process consumes a lot of manual cost and is difficult to achieve accurate annotation. To further reduce the annotation burden, we propose an IR small target mask generation algorithm based on single-point supervised multi-scale chain growth clustering (MCGC). The core of this work is the adaptive generation of IR small-target pseudo mask maps under the supervision of randomly given single-point labels, sequentially through the strategies of multi-scale chain growth, Euclidean coefficient decay, K-Means clustering, and eight-neighborhood clustering. On the four public datasets, ablation experiments, qualitative and quantitative comparison experiments demonstrate that the MCGC algorithm has an efficient and accurate IR small target pseudo mask generation capability, which can be adapted to different numbers, scales, shapes, and intensities of targets in complex backgrounds. In addition, IR-Labelmask, an IR small target mask annotation software designed based on the MCGC algorithm, is publicly available on kourenke/IR-Labelmask-software (github.com). To our knowledge, this is the first mask annotation software designed for IR small target.
