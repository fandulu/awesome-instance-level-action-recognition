# awesome-instance-level-action-recognition


## Why awesome instance-levelaction action recognition?

This is a collection of papers and resources for instance-levelaction action recognition


## Table of Contents
- [Datasets](#datasets)
- [Papers](#papers)

## Datasets
*Note that, although datasets like UCF-101 have SpatioTemporal annotations, the action tube ID may not be consistent with person ID. For example, after the same person changing his/her action, the corresponding action tube ID changed while the person ID should remain the same. Person ID is not available in those datasets (e.g., UCF-101, UCF-Sports, JHMDB). It is challenging to using them for instance-level action recognition datasets. We have to use the datasets that not only have an instance-level action label for each person but also have the MOT labels.
<img src="https://github.com/fandulu/awesome-instance-level-action-recognition/blob/main/images/tube_person_ID.jpg" width="550">


 
<details>
<summary>ActEv Dataset [monocular-view movies, 35 action labels, labeling every 30 FPS w/ MOT label and action label]</summary>
 <div align="center">
  <img src="images/ava_demo.gif" width="600px"/>
</div>
 
[link](https://actev.nist.gov/trecvid20#tab_data)
 </details>
 
 
<details>
<summary>PANDA Dataset [super-resolution monocular-view movies, labeling every FPS w/ MOT label and action label]</summary>
 <div align="center">
  <img src="images/panda.png" width="600px"/>
</div>
 
[link](http://www.panda-dataset.com/index.html)
 </details>
 

## Papers of IAR (Instance-level Action Recognition)
<details>
<summary>Argus: Efficient activity detection system for extended video analysis (WACVW2020)</summary>
 
 [pdf](https://openaccess.thecvf.com/content_WACVW_2020/papers/w5/Liu_Argus_Efficient_Activity_Detection_System_for_Extended_Video_Analysis_WACVW_2020_paper.pdf)
 [codes]()
 
@inproceedings{liu2020argus,
  title={Argus: Efficient activity detection system for extended video analysis},
  author={Liu, Wenhe and Kang, Guoliang and Huang, Po-Yao and Chang, Xiaojun and Qian, Yijun and Liang, Junwei and Gui, Liangke and Wen, Jing and Chen, Peng},
  booktitle={Proceedings of the IEEE Winter Conference on Applications of Computer Vision Workshops},
  pages={126--133},
  year={2020}
}
</details>



## 360◦ Videos SAL/D

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


## SAL/D

### Datasets

<details>
<summary>AVA: A Video Dataset of Spatio-temporally Localized Atomic Visual Actions (CVPR2018)</summary>
 
 (AVA) [pdf](https://arxiv.org/pdf/1705.08421.pdf)
 
@inproceedings{gu2018ava,
  title={Ava: A video dataset of spatio-temporally localized atomic visual actions},
  author={Gu, Chunhui and Sun, Chen and Ross, David A and Vondrick, Carl and Pantofaru, Caroline and Li, Yeqing and Vijayanarasimhan, Sudheendra and Toderici, George and Ricco, Susanna and Sukthankar, Rahul and others},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={6047--6056},
  year={2018}
}
</details>


<details>
<summary>The AVA-Kinetics Localized Human Actions Video Dataset (Arxiv2020)</summary>
 
 (AVA-Kinetics) [pdf](https://arxiv.org/pdf/2005.00214.pdf)
 
@article{li2020ava,
  title={The AVA-Kinetics Localized Human Actions Video Dataset},
  author={Li, Ang and Thotakuri, Meghana and Ross, David A and Carreira, Jo{\~a}o and Vostrikov, Alexander and Zisserman, Andrew},
  journal={arXiv preprint arXiv:2005.00214},
  url = {https://arxiv.org/abs/2005.00214},
  year={2020}
}
</details>


<details>
<summary> Spot On: Action Localization from Pointly-Supervised Proposals (ECCV2016)</summary>
 
 (Hollywood2Tubes) [pdf](https://arxiv.org/pdf/1604.07602.pdf)
 
@inproceedings{mettes2016spot,
  title={Spot on: Action localization from pointly-supervised proposals},
  author={Mettes, Pascal and Van Gemert, Jan C and Snoek, Cees GM},
  booktitle={European conference on computer vision},
  pages={437--453},
  year={2016},
  organization={Springer}
}
</details>


<details>
<summary> Human Action Localization with Sparse Spatial Supervision (ECCV2016)</summary>
 
 (DALY) [pdf](https://arxiv.org/pdf/1605.05197.pdf)
 
@article{weinzaepfel2016human,
  title={Human action localization with sparse spatial supervision},
  author={Weinzaepfel, Philippe and Martin, Xavier and Schmid, Cordelia},
  journal={arXiv preprint arXiv:1605.05197},
  url = {https://arxiv.org/pdf/1605.05197.pdf},
  year={2016}
}
</details>



<details>
<summary> Action Recognition in Realistic Sports Videos (CVPR2008)</summary>
 
 (UCF Sports) [pdf](https://cs.stanford.edu/~amirz/index_files/Springer2015_action_chapter.pdf)

@inproceedings{rodriguez2008action,
  title={Action mach a spatio-temporal maximum average correlation height filter for action recognition},
  author={Rodriguez, Mikel D and Ahmed, Javed and Shah, Mubarak},
  booktitle={2008 IEEE conference on computer vision and pattern recognition},
  pages={1--8},
  year={2008},
  organization={IEEE}
}
</details>


### Technique Papers

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
 
@article{girdhar2018better,
  title={A better baseline for ava},
  author={Girdhar, Rohit and Carreira, Jo{\~a}o and Doersch, Carl and Zisserman, Andrew},
  journal={arXiv preprint arXiv:1807.10066},
  url = {https://arxiv.org/abs/1807.10066}
  year={2018}
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
<summary>Online Real-time Multiple Spatiotemporal Action Localisation and Prediction (CVPR2017)</summary>
 
 [pdf](https://arxiv.org/pdf/1611.08563.pdf)
 [code](https://github.com/gurkirt/corrected-UCF101-Annots)
 
@inproceedings{singh2017online,
  title={Online real-time multiple spatiotemporal action localisation and prediction},
  author={Singh, Gurkirt and Saha, Suman and Sapienza, Michael and Torr, Philip HS and Cuzzolin, Fabio},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  pages={3637--3646},
  year={2017}
}
</details>


<details>
<summary>Tube Convolutional Neural Network (T-CNN) for Action Detection in Videos (ICCV2017)</summary>
 
 [pdf](https://arxiv.org/pdf/1703.10664.pdf)
 [code](http://crcv.ucf.edu/projects/TCNN/)
 
@inproceedings{hou2017tube,
  title={Tube convolutional neural network (T-CNN) for action detection in videos},
  author={Hou, Rui and Chen, Chen and Shah, Mubarak},
  booktitle={Proceedings of the IEEE international conference on computer vision},
  pages={5822--5831},
  year={2017}
}
</details>


<details>
<summary>TORNADO: A Spatio-Temporal Convolutional Regression Network for Video Action Proposal (ICCV2017)</summary>
 
 [pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_TORNADO_A_Spatio-Temporal_ICCV_2017_paper.pdf)
 
@inproceedings{zhu2017tornado,
  title={Tornado: A spatio-temporal convolutional regression network for video action proposal},
  author={Zhu, Hongyuan and Vial, Romain and Lu, Shijian},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  pages={5813--5821},
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

