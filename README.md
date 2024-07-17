# CUDA_Pyramid

1.
```
cd cuda-samples-master/Samples/5_Domain_Specific/CUDAPYM
```
其中main.cpp line154 
```
  const int nLevels = 4;
```
可以修改迭代层数 必须是整数（1~N）

2.编译
```
make
```
3.运行
```
./HSOpticalFlow
```
输出运行结果在同目录下GPUout.ppm
修改main.cpp line162 可以修改输出结果位置

4.输出PPM格式转png格式

```
cd cuda-samples-master/xcb_scripts
python ppm2png.py
```
输出结果在TestData
输入输出可以自己修改
