# gulou-blackboard-3d-reconstruction
此项目计划使用传统计算机视觉方法，利用互联网收集的图片，对南京大学鼓楼校区中南园教学楼花坛前侧的黑板进行3d重建。

这是一个个人的兴趣项目。欢迎有兴趣的同学一起参与到项目的讨论和开发。工作很忙，下班和周末有空会写一写，项目进展不定期。

## Introduction
最近学校的鼓楼校区南园的黑板被拆掉了，心里还是蛮难受的。正好自己所做的工作是计算机视觉相关，所以想着能不能在自己的专业上为学校的同学老师们帮一些忙。

众所周知，计算机视觉的应用是很广泛的。其中一个比较常见的应用是利用立体视觉进行三维重建，例如对一些文物进行数字存档和实地测量。在几年前的巴黎圣母院失火事件中，育碧在其制作的游戏：*Assassin’s Creed Unity*中，对巴黎圣母院的建模也一定程度上对文物的信息起到了保护作用。取决于实地测量和对信息进行存档的精细程度，倘若文物因为人为或者是自然灾害（如地震、洪水、酸雨、闪电等）而受到损毁，这些珍贵的数字信息将对文物修复与重建工作提供宝贵的参考资料。

## 设计方案
预期得到的结果是一个colored mesh。

### 论文引用和参考资料
http://media.gisera.com/jsjl/show/329.aspx

Y. Furukawa, J. Ponce, Accurate camera calibration from multi-view stereo and bundle adjustment, Int. J. Comput. Vision, 84 (2009) 257-268.

https://zhuanlan.zhihu.com/p/76047709

Occluding Contours for Multi-View Stereo, http://grail.cs.washington.edu/projects/sq_rome_g2/
