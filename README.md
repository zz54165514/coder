
#我们是从代码到实物课程的第六组，我们的项目是“基于机器视觉检测的智能动态节电广告牌”<br>
###小组成员：<br>
###毛宇昕 2016111031<br>
###唐衡璇 2016112646<br>
###朱海   2016113472<br>
###廖川黎 2017114837<br>
###段烨   2017111924<br>
##项目主要分为三大部分：<br>
###①人脸检测代码的编写，这一部分主要分为：<br>
###基于人脸样本以及Adaboost算法提取人脸的Haar特征，训练用于此场景下的级联分类器<br>
###基于训练好的级联分类器完成人脸检测的部分，其中使用opencv封装好的类可以很轻松地完成这部分代码的编写<br>
##②串口通信函数的编写<br>
###由于上位机的代码是基于VS编写的C++代码，无法直接下载到Arduino上，因此需要建立上位机与控制电路之间的通信，串口通过向Arduino发送不同指令，从而完成“广告牌”亮度的变化<br>
##③Arduino程序的编写<br>
###这一部分比较容易，因为我们项目的创新点与难点主要集中于以上两部分，这一部分主要就是使用Arduino控制8*8点阵实现了不同的功能，加之读串口的函数
