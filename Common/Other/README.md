###########################################################################################################
function linesIntersection

参考http://paulbourke.net/geometry/pointlineplane/

p0 p1 为三维空间中第一条直线上两点，p2 p3为三维空间中第二条直线上两点

###########################################################################################################
function getCorrectedPose

用于求当旋转中心发生变化后原Pose对应的新的Pose应该为多少。

###########################################################################################################
AdaptivePSO方法原理见论文《Adaptive Particle Swarm Optimization》DOI: 10.1109/TSMCB.2009.2015956

DualQuaternion_gtc处理对偶四元数，主要增加sclerp、DIB两种插值方法

AdaptivePSO_DQ结合apso和对偶四元数方法对Pose进行优化
