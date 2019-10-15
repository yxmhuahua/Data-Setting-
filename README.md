# Data-Setting-
Data Setting on our own dataset
在整理分割数据集时，采用的是Id检索，每次会遍历xml注释文件，
所以效率很低，最好的方法应该是以每个注释文件为单位进行处理，但是相对最耗时的应该是存储图像，
所以影响可以接受，其次只用CPU进行处理，处理速度也是很慢！
