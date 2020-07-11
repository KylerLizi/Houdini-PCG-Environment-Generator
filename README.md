# Houdini-PCG-Environment-Generator
* [【UE4+Houdini+Bridge】程序化地形生成山谷环境制作思路 —— CSDN](https://blog.csdn.net/qq_31788759/article/details/106216288)<br>
* [Houdini To UE4 程序化地形生成制作过程与效果展示 —— bilibili](https://www.bilibili.com/video/BV1aQ4y1A7Du/)<br>
基于Houdini制作的程序化生成野外场景模型摆放的HDA工具。<br>
![UE4Viewpot](https://github.com/ColorGalaxy/Houdini-PCG-Environment-Generator/raw/master/Screenshot/UE4Viewpot.png)<br>
### 资产简介
首先通过HeightField结合Mask创建地形与layer，然后根据自然环境模拟植被撒点，最后将得到的包含位置点云数据与模型实例输入的HDA导入UE4。<br>
在UE4中制作好Layer对应的地形材质，在Quixel中筛选扫描级模型贴图资源，替换掉Houdini Input中的模型，即可生成能够通过HDA实时调节的大世界野外场景。<br>
![HoudiniViewport](https://github.com/ColorGalaxy/Houdini-PCG-Environment-Generator/raw/master/Screenshot/HoudiniViewport.png)<br>