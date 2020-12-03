# DCNv2

## 概述

I implement deformable convolutional networks v2 with keras (tensorflow). This is an example how to use it:

https://github.com/miemie2013/Keras-PPYOLO-YOLOv4

I use DCNv2 in ResNet50vd's 5th stage.


我在Keras(Tensorflow)上实现了可变形卷积DCNv2，这是一个使用DCNv2的示例:

https://github.com/miemie2013/Keras-PPYOLO-YOLOv4

我在ResNet50vd的第五个stage使用了DCNv2。


2020/11/05:经过不懈努力，咩酱终于在Keras上实现了可变形卷积DCNv2！这应该是咩酱最自豪的工作了。之前的种种算法（如CenterNet）因为使用了可变形卷积，而Keras、tensorflow官方没有实现可变形卷积，使得这些算法无缘在Keras平台大显身手。
而咩酱不才，一直都无法实现这一算法。经过差不多两年对算法的学习，对深度学习框架的理解，这次我再次挑战实现可变形卷积，终于大获全胜！
值得一提的是这次的DCNv2并不需要读者编译什么c、c++、cuda、自定义op这些玩意！因为这是用tensorflow的纯python接口实现，效率极高，是咩酱的得意之作！
带有DCNv2的PPYOLO，速度超过了不带有DCNv2的YOLOv4，咩酱也亲自与Pytorch版的PPYOLO（https://github.com/miemie2013/Pytorch-PPYOLO ）测过FPS，速度持平，可见实现的DCNv2效率极高。
其实一开始我并不想干这么费脑子的事情，但是抬头不见低头见，多造轮子其实是件好事，自己就会得到锻炼。下面我们来一览PPYOLO与YOLOv4的神采吧：

## 传送门

咩酱重写过很多算法，比如PPYOLO、SOLOv2、FCOS、YOLOv4等，而且在多个深度学习框架（tensorflow、pytorch、paddlepaddle等）上都实现了一遍，你可以进我的GitHub主页看看，看到喜欢的仓库可以点个star呀！

cv算法交流q群：645796480
但是关于仓库的疑问尽量在Issues上提，避免重复解答。

本人微信公众号：miemie_2013

技术博客：https://blog.csdn.net/qq_27311165

AIStudio主页：[asasasaaawws](https://aistudio.baidu.com/aistudio/personalcenter/thirdview/165135)

欢迎在GitHub或AIStudio上关注我（求粉）~

## 打赏

如果你觉得这个仓库对你很有帮助，可以给我打钱↓
![Example 0](weixin/sk.png)

咩酱爱你哟！另外，有偿接私活，可联系微信wer186259，金主快点来吧！
