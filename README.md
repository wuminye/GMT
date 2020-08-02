# Visual Tracking with Multiview Trajectory Prediction

(Under Construction)

"Visual Tracking with Multiview Trajectory Prediction" <br>
Minye Wu, Haibin Ling, Ning Bi, Shenghua Gao, Qiang Hu, Hao Sheng,  Jingyi Yu

# Abstract
Recent progresses in visual tracking have greatly improved the tracking performance. However, challenges such as occlusion and view change remain obstacles in real world deployment. A natural solution to these challenges is to use multiple cameras with multiview inputs, though existing systems are mostly limited to specific targets (e.g. human), static cameras, and/or require camera calibration.
To break through these limitations, we propose a generic multiview tracking (GMT) framework that allows camera movement, while requiring neither specific object model nor camera calibration. A key innovation in our framework is a cross-camera trajectory prediction network (TPN), which implicitly and dynamically encodes camera geometric relations, and hence addresses missing target issues such as occlusion. Moreover, during tracking, we assemble information across different cameras to dynamically update a novel collaborative correlation filter (CCF), which is shared among cameras to achieve robustness against view change. The two components are integrated into a correlation filter tracking framework, where features are trained offline using existing single view tracking datasets. For evaluation, we first contribute a new generic multiview tracking dataset (GMTD) with careful annotations, and then run experiments on the GMTD and CAMPUS datasets. The proposed GMT algorithm shows clear advantages in terms of robustness over state-of-the-art ones.


# Generic  Multiview  Tracking  Dataset (GMTD)
GMTD is released for non-commercial purposes.  [Google Drive](https://drive.google.com/file/d/1TPQe-nfUiTK9d9lV8m_cniP24qKHB2Nw/view?usp=sharing)
