# LBP
获取图像的LBP特征：对图像的原始LBP模式、等价LBP模式、旋转不变LBP模式，以及等价旋转不变LBP模式的LBP特征进行提取以及显示。

get_LBP_from_Image.py  主要文件 获取图像的LBP特征

get_resolve_map.py和get_uniform_map.py主要是做降维后新的像素值的映射。已经将求出的结果写入了get_LBP_from_Image.py中，这两个主要是帮助理解算法降维后新的像素值怎么得到的。