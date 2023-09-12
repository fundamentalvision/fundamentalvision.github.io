---
title: Foundation Model for Visual Perception
---

# {% include icon.html icon="fa-solid fa-wrench" %}Foundation Model for Visual Perception

Object detection and recognition are the basic problems of visual perception. We focus on designing vision backbones and object detection models to solve these problems and extending them to universal and large-scale foundation models for general perception tasks.

## Representative work:

### Object detection models with high precision and efficiency

<table width=100%>
  <tr>
    <td width=50% valign="top">
      <strong><a href="https://arxiv.org/abs/1605.06409">R-FCN: Object Detection via Region-based Fully Convolutional Networks</a></strong><br>
      <alert>[NIPS 2016 3rd most influential paper]</alert><br>
      <alert>[Pytorch standard operator]</alert><br>
    </td>
    <td width=50% valign="top">
      <strong><a href="https://arxiv.org/abs/2010.04159">Deformable DETR: Deformable Transformers for End-to-End Object Detection</a></strong><br>
      <alert>[ICLR 2021 2nd most influential paper]</alert><br>
    </td>
  </tr>
  <tr>
    <td width=50%>
      <img width="80%" src="../images/r-fcn.png" align="center"/>
    </td>
    <td width=50%>
      <img width="80%" src="../images/deformable_detr.png" align="center"/>
    </td>
  </tr>
</table>

<!--
- [**R-FCN: Object Detection via Region-based Fully Convolutional Networks**](https://arxiv.org/abs/1605.06409)

[Ranking 3rd of the most influential papers in NIPS 2016]
[Selected into the operator library of Pytorch]

<br>
<div align="center">
  <img width="60%" src="../images/r-fcn.png"/>
</div>
<br>

- [**Deformable DETR: Deformable Transformers for End-to-End Object Detection**](https://arxiv.org/abs/2010.04159)

[Ranking 2nd of the most influential papers in ICLR 2021]

<br>
<div align="center">
  <img width="60%" src="../images/deformable_detr.png"/>
</div>
<br>
-->

### Vision backbones with deformable convolutions & large-scale vision backbones

<table width=100%>
  <tr>
    <td width=50% valign="top">
      <strong>Deformable Convolutional Networks 
      <a href="https://arxiv.org/abs/1703.06211">v1</a>/
      <a href="https://arxiv.org/abs/1811.11168">v2</a></strong><br>
      <alert>[ICCV 2017 6th most influential paper]</alert><br>
      <alert>[Pytorch standard operator]</alert><br>
    </td>
    <td width=50% valign="top">
      <strong><a href="https://arxiv.org/abs/2211.05778">InternImage: Exploring Large-Scale Vision Foundation Models with Deformable Convolutions</a></strong><br>
      <alert>[CVPR 2023 highlight paper]</alert><br>
    </td>
  </tr>
  <tr>
    <td width=50%>
      <img width="80%" src="../images/dcn.png" align="center"/>
    </td>
    <td width=50%>
      <img width="50%" src="../images/dcn-v3.png" align="center"/>
    </td>
  </tr>
</table>

<!--
- **Deformable Convolutional Networks** [**v1**](https://arxiv.org/abs/1703.06211)/[**v2**](https://arxiv.org/abs/1811.11168)

[Ranking 6th of the most influential papers in ICCV 2017]
[Selected into the operator library of Pytorch]

<br>
<div align="center">
  <img width="60%" src="../images/dcn.png"/>
</div>
<br>

- [**InternImage: Exploring Large-Scale Vision Foundation Models with Deformable Convolutions**](https://arxiv.org/abs/2211.05778) 

[CVPR 2023 highlight paper]

<br>
<div align="center">
  <img width="45%" src="../images/dcn-v3.png"/>
</div>
<br>
-->