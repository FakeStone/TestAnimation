# TestAnimation


2016年3月29日 星期二
13:43

#在安卓中使用动画

动画分为补间动画和帧动画
补间动画只是针对一张图
帧动画是多张图


##补间动画
补间动画涉及图片的透明alpha
旋转translate 放大缩小scale
动画都是针对一张图片的所以使用步骤是：
1.新建AnimationSet
2.新建AlphaAnimation ScaleAnimation TranslateAnimation
  新建的时候就直接传入参数，调用duration设置动画持续时间
3.AnimationSet.add加入动画

4.imageView设置该AnimationSet
