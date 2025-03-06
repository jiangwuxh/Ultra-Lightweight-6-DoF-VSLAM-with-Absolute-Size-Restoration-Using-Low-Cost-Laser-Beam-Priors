Ultra-Lightweight 6-DoF VSLAM with Absolute Size Restoration Using Low-Cost Laser Beam Priors

Hao Xu1,#, Liping Li2,#, Xixiang Liu3,*
1. Key Laboratory of Micro-inertial Instrument and Advanced Navigation Technology, Ministry of Education, Southeast University
2. College of Electronic Engineering, Nanjing Xiaozhuang University
3. Ministry of Education, Southeast University

Abstract
Visual Simultaneous Localization and Mapping (VSLAM) technology is widely utilized due to its advantages, yet it inherently lacks absolute size information. Existing 6-DoF VSLAM solutions often incorporate additional sensor data to address this limitation, making them impractical for resource-constrained applications. In this paper, we present a novel method for achieving 6-DoF VSLAM using a low-cost laser beam as a spatial constraint prior. By integrating the absolute depth information provided by the laser beam into the visual motion estimation framework, we successfully restore the absolute size and control size drift. Our method minimizes sensor requirements and computational overhead, using only a single camera and a low-cost laser beam emitter (costing $1 or less). Extensive experiments on hardware and datasets demonstrate that our method achieves accurate size restoration and efficient pose estimation, significantly reducing computational power consumption (by 27% compared to ORB-SLAM3 and VINS-Mono). The proposed approach is ultra-lightweight and cost-effective, making it ideal for deployment on platforms with limited resources.

Keywords: 6-DoF VSLAM, ultra-lightweight SLAM, size restoration, spatial constraint, prior information

This paper introduces a novel approach for size restoration in 5-DoF VSLAM, leveraging the spatial constraint of light beam as the prior information to enable absolute size restoration. This approach is both uncomplicated and ultra-lightweight, requiring only the addition of a low-cost ($1 or less) beam emitter attached to the camera. Experiments demonstrate that the proposed method provides smooth operation, prominently decreases computational time, and achieves above 27% improvement in timeliness performance compared to existing SOTA visual size restoration techniques. Owing to its low hardware requirements and efficient processing, this algorithm is well suited for deployment on platforms with limited resources.
