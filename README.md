# awesome-instance-level-action-recognition


## Why awesome instance-levelaction action recognition?

This is a collection of papers and resources for instance-levelaction action recognition


## Table of Contents
- [Datasets](#datasets)
- [Papers](#papers)

## Datasets
*Note that, since datasets, like UCF Sports and JHMDB, have SpatioTemporal Annotations but do not have the unique ID assignment for each person, it is challenging to using them for instance-level action recognition datasets. The AVA ID assignment labels are available in the TAO dataset.

<details>
<summary>AVA Actions Dataset [monocular-view movies, 80 action labels, labeling every 30 FPS]</summary>
 <div align="center">
  <img src="images/ava_demo.gif" width="600px"/>
</div>
 
[link](http://research.google.com/ava/)
 </details>
 
 
 
<details>
<summary>ActEv Dataset [monocular-view movies, 35 action labels, labeling every 30 FPS]</summary>
 <div align="center">
  <img src="images/ava_demo.gif" width="600px"/>
</div>
 
[link](https://actev.nist.gov/trecvid20#tab_data)
 </details>
 
 
<details>
<summary>PANDA Dataset [super-resolution monocular-view movies, labeling every FPS]</summary>
 <div align="center">
  <img src="images/panda.png" width="600px"/>
</div>
 
[link](http://www.panda-dataset.com/index.html)
 </details>
 



## Papers
### Dataset Papers

<details>
<summary>AVA: A Video Dataset of Spatio-temporally Localized Atomic Visual Actions (CVPR2018)</summary>
 
 [pdf](https://arxiv.org/pdf/1705.08421.pdf)
 
@inproceedings{gu2018ava,
  title={Ava: A video dataset of spatio-temporally localized atomic visual actions},
  author={Gu, Chunhui and Sun, Chen and Ross, David A and Vondrick, Carl and Pantofaru, Caroline and Li, Yeqing and Vijayanarasimhan, Sudheendra and Toderici, George and Ricco, Susanna and Sukthankar, Rahul and others},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={6047--6056},
  year={2018}
}
</details>


## Technique Papers

<details>
<summary>CFAD: Coarse-to-Fine Action Detector for Spatiotemporal Action Localization(ECCV2020)</summary>
 
 [pdf](https://arxiv.org/pdf/2008.08332.pdf)
 
@inproceedings{li2020cfad,
  title={CFAD: Coarse-to-Fine Action Detector for Spatiotemporal Action Localization},
  author={Li, Yuxi and Lin, Weiyao and See, John and Xu, Ning and Xu, Shugong and Yan, Ke and Yang, Cong},
  booktitle={European Conference on Computer Vision},
  pages={510--527},
  year={2020},
  organization={Springer}
}
</details>




<details>
<summary>Actions as Moving Points (ECCV2020)</summary>
 
 [pdf](https://arxiv.org/pdf/2001.04608.pdf)
 [code](https://github.com/MCG-NJU/MOC-Detector)
 
@article{li2020actions,
  title={Actions as Moving Points},
  author={Li, Yixuan and Wang, Zixu and Wang, Limin and Wu, Gangshan},
  journal={arXiv preprint arXiv:2001.04608},
  year={2020}
}
</details>



<details>
<summary>Actor-context-actor relation network for spatio-temporal action localization (Arxiv2020)</summary>
 
 [pdf](https://arxiv.org/pdf/2006.07976v2.pdf)
 [code](https://github.com/Siyu-C/ACAR-Net)
 
@article{pan2020actor,
  title={Actor-context-actor relation network for spatio-temporal action localization},
  author={Pan, Junting and Chen, Siyu and Shou, Zheng and Shao, Jing and Li, Hongsheng},
  journal={arXiv preprint arXiv:2006.07976},
  url = {https://arxiv.org/pdf/2006.07976v2.pdf},
  year={2020}
}
</details>



<details>
<summary>A Better Baseline for AVA (CVPRW2018)</summary>
 
 [pdf](https://arxiv.org/pdf/1807.10066.pdf)
 
@inproceedings{kalogeiton2017action,
  title={Action tubelet detector for spatio-temporal action localization},
  author={Kalogeiton, Vicky and Weinzaepfel, Philippe and Ferrari, Vittorio and Schmid, Cordelia},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  pages={4405--4413},
  year={2017}
}
</details>



<details>
<summary>Action Tubelet Detector for Spatio-Temporal Action Localization (ICCV2017)</summary>
 
 [pdf](http://thoth.inrialpes.fr/src/ACTdetector/)
 [code](https://github.com/vkalogeiton/caffe/tree/act-detector)
 
@inproceedings{kalogeiton2017action,
  title={Action tubelet detector for spatio-temporal action localization},
  author={Kalogeiton, Vicky and Weinzaepfel, Philippe and Ferrari, Vittorio and Schmid, Cordelia},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  pages={4405--4413},
  year={2017}
}
</details>


<details>
<summary>Learning to track for spatio-temporal action localization (ICCV2015)</summary>
 
 [pdf](https://openaccess.thecvf.com/content_iccv_2015/papers/Weinzaepfel_Learning_to_Track_ICCV_2015_paper.pdf)
 
@inproceedings{weinzaepfel2015learning,
  title={Learning to track for spatio-temporal action localization},
  author={Weinzaepfel, Philippe and Harchaoui, Zaid and Schmid, Cordelia},
  booktitle={Proceedings of the IEEE international conference on computer vision},
  pages={3164--3172},
  year={2015}
}
</details>



* [Tube Convolutional Neural Network (T-CNN) for Action Detection in Videos](https://arxiv.org/pdf/1703.10664.pdf) - [R. Hou](http://www.cs.ucf.edu/~rhou/) et al, ICCV2017. [[project web]](http://crcv.ucf.edu/projects/TCNN/)
* [TORNADO: A Spatio-Temporal Convolutional Regression Network for Video Action Proposal](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_TORNADO_A_Spatio-Temporal_ICCV_2017_paper.pdf) - H. Zhu et al., ICCV2017. 
