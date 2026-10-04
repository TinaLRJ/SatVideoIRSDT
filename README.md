# SatVideoIRSDT dataset: Infrared video satellite aerial moving target detection dataset
Infrared video satellites serve as critical tools for detecting aerial moving targets, with infrared small target detection technology forming the essential foundation for this capability. The rapid advancement of deep learning has yielded numerous single-frame detection datasets and methodologies, enabling significant progress in identifying spatially salient targets. However, moving aerial targets captured by infrared satellites typically exhibit low spatial salience and frequently occur in complex scenarios, rendering single-frame detection methods reliant on spatial information ineffective in such challenging conditions. This urgent challenge necessitates the development of multi-frame infrared small and dim target detection techniques. A major bottleneck restricting the advancement and practical application of aerial moving target detection technology has been the lack of dedicated datasets for infrared video satellite-based detection, primarily due to the difficulties and high costs associated with data collection and annotation. To address this gap and promote technological development, we construct the first infrared video satellite aerial moving target detection dataset containing many real-world scenarios, called SatVideoIRSDT dataset, and organized the inaugural detection competition based on this dataset. First, we collect 20126 frames of real infrared video satellite data from Wuhan No.1 satellite featuring aerial moving targets and annotate 29757 aerial targets. Then, we integrate two simulated infrared aerial moving target datasets with authentic space-based backgrounds to enhance scenario diversity. The resulting dataset comprises 1401 real scenarios, 122265 video frames, and 454116 annotated targets, with mask labels distinguishing different target instances to support both detection and tracking research.

Dataset download path: [Science Data Bank](https://doi.org/10.57760/sciencedb.j00240.00077)

## Citiation for SatVideoIRSDT Dataset
```
@article{li2026satvideodataset,
  title={Infrared video satellite aerial moving target detection dataset and its evaluation},
  author={Li, Ruojing and Li, Zhaoxu and Chen, Nuo and Guo, Gaowei and Dou, Zechao and Long, Zhengxing and Luo, Yihang and Zeng, Yaoyuan and Sheng, Weidong and Li, Boyang and others},
  doi={10.11834/jig.250536},
  journal={Journal of Image and Graphics},
  pages={1--15},
  year={2026}
}
@article{li2025dataset,
  title={Infrared video satellite aerial moving target detection dataset},
  author={Li, Ruojing and Zeng, Yaoyuan and Sheng, Weidong and Li, Boyang and Li, Zhaoxu and Chen, Nuo and Guo, Gaowei and Dou, Zechao and Long, Zhengxing and Luo, Yihang and others},
  doi={10.57760/sciencedb.j00240.00077},
  url={https://doi.org/10.57760/sciencedb.j00240.00077},
  year={2025},
  publisher={Science Data Bank}
}
```

## IRAir数据集已公布
Github仓库：https://github.com/TinaLRJ/IRAir-dataset
