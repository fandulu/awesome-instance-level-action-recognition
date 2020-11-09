# awesome-instance-level-action-recognition


## Why awesome instance-levelaction action recognition?

This is a collection of papers and resources for instance-levelaction action recognition


## Table of Contents
- [Datasets](#datasets)
- [Papers](#papers)

## Datasets

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
 
 <details>
<summary>360-Degree Actions Dataset [360-degrees surveillance videos, 19 action labels]</summary>
 <div align="center">
  <img src="images/360.png" width="900px"/>
</div>
 
[link](https://github.com/ryukenzen/360action)
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



<details>
<summary>Weakly-Supervised Multi-Person Action Recognition in 360◦ Videos (WACV2020)</summary>
 
 [pdf](https://openaccess.thecvf.com/content_WACV_2020/papers/Li_Weakly-Supervised_Multi-Person_Action_Recognition_in_360circ_Videos_WACV_2020_paper.pdf)
 [code](https://github.com/ryukenzen/360action)
 
 @inproceedings{li2020weakly,
  title={Weakly-Supervised Multi-Person Action Recognition in 360° Videos},
  author={Li, Junnan and Liu, Jianquan and Wang, Yongkang and Nishimura, Shoji and Kankanhalli, Mohan S},
  booktitle={2020 IEEE Winter Conference on Applications of Computer Vision (WACV)},
  pages={497--505},
  year={2020},
  organization={IEEE}
}
</details>

## Technique Papers

<details>
<summary>A Better Baseline for AVA (Arxiv2020)</summary>
 
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



* [Tube Convolutional Neural Network (T-CNN) for Action Detection in Videos](https://arxiv.org/pdf/1703.10664.pdf) - [R. Hou](http://www.cs.ucf.edu/~rhou/) et al, ICCV2017. [[project web]](http://crcv.ucf.edu/projects/TCNN/)
* [TORNADO: A Spatio-Temporal Convolutional Regression Network for Video Action Proposal](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_TORNADO_A_Spatio-Temporal_ICCV_2017_paper.pdf) - H. Zhu et al., ICCV2017. 
