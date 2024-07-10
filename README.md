# MRDNet: Single Image Reflection Removal From Glass Surfaces via Multi-Scale Reflection Detection

**Tao Yan, Helong Li, Jiahui Gao, Zhengtian Wu and Rynson W. H. Lau, "Single Image Reflection Removal From Glass Surfaces Via Multi-scale Reflection Detection," IEEE Transactions on Consumer Electronics (TCE), vol. 69, issue 4, pp. 1164-1176, Nov. 2023, doi: 10.1109/TCE.2023.3303475. <a href="https://ieeexplore.ieee.org/document/10214078">doi: 10.1109/TCE.2023.3303475</a>**

> Abstract—While people take photos through glass surfaces with consumer imaging equipments, such as smartphones or digital cameras, reflections on the glass surfaces of captured images cannot be avoided. Reflections not only affect the aesthetic perception of captured images but also degrade the performance of subsequent tasks. Since the prominence of reflections depends on the contrast between the foreground reflection layer and the background transmission layer, reflections on different regions of the same glass surface may have extremely different sizes and brightness contrasts. In this paper, we propose a reflection removal network, named MRDNet, with a novel multi-scale reflection detector for foreground reflection detection and a novel Multi-scale Reflection-aware Transmission Recovery (MRTR) module for background transmission layer restoration. Our MRDNet has three main modules. First, two parallel feature extraction modules, called Reflection Extractor (R-Extractor) and Transmission Extractor (T-Extractor), are introduced to extract features of the foreground reflection layer and features of the background transmission layer contaminated by reflections, from the input image, respectively. Then, a Multi-scale Reflection aware Transmission Recovery (MRTR) module is proposed to recover textural details of the background transmission layer. For learning our network, we also propose a large scale 3D virtual world Physical Rendering-based Reflection Removal (PRGR) dataset.

## Result Comparisons

<p align="center">
  <img src="https://github.com/YT3DVision/MRDNet/blob/main/figure/result.png" style="width:100%" />
</p>

## Network Architecture

<p align="center">
  <img src="https://github.com/YT3DVision/MRDNet/blob/main/figure/network.jpg" style="width:100%" />
</p>

## Dataset

**The dataset can be obtained from <a href="https://pan.baidu.com/s/14kr765l96onBKHVkekchyA?pwd=1234">Baidu Netdisk</a> or <a href="https://drive.google.com/file/d/1HPjHTzpbhJ1dclXntXHTq4z424uu3xSg/view?usp=sharing">Google Drive</a>.**

