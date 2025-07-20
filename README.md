# Research Papers

## Content
1. [Medical Image Semantic Segmentation](#medical-image-semantic-segmentation)
2. [Classic Model](#classic_model)
3. [Dataset Resources](#dataset-resources)

---

<a id="medical-image-semantic-segmentation"></a>
## Medical Image Semantic Segmentation

1. [2025 MICCAI] Conservative-Radical Complementary Learning for Class-incremental Medical Image Analysis with Pre-trained Foundation Models [[paper]](https://arxiv.org/pdf/2407.13768)  
   提出保守-激进互补学习策略，解决医学图像中的类别增量学习问题
2. [2025 MICCAI] D-CAM: Learning Generalizable Weakly-Supervised Medical Image Segmentation from Domain-invariant CAM [[paper]](待补充) [[code]](https://github.com/JingjunYi/D-CAM)  
   D-CAM：基于领域不变类激活图的泛化性弱监督医学图像分割方法  
3. [2025 MICCAI] Semi-Supervised Multi-Modal Medical Image Segmentation for Complex Situations [[paper]](https://arxiv.org/pdf/2506.17136)  
   半监督医学图像分割的关键在于伪标注的生成，采用transCLIP的方法对伪标签进行矫正  
4. [2025 CVPR] Prototype-Based Image Prompting for Weakly Supervised Histopathological Image Segmentation [[paper]](https://arxiv.org/pdf/2503.12068)[[code]](https://github.com/QingchenTang/PBIP?tab=readme-ov-file)  
   基于原型图像提示的弱监督病理图像分割  
5. [2025 CVPR] Multi-modal Topology-embedded Graph Learning for Spatially Resolved Genes Prediction from Pathology Images with Prior Gene Similarity Information [[paper]](https://openaccess.thecvf.com/content/CVPR2025/papers/Shi_Multi-modal_Topology-embedded_Graph_Learning_for_Spatially_Resolved_Genes_Prediction_from_CVPR_2025_paper.pdf)[[code]](https://github.com/MedAIerHHL/CVPR-MIA)  
   基于多模态拓扑嵌入图学习的病理图像空间解析基因预测——融合先验基因相似性信息  
6. [2025 CVPR] VLSA: Interpretable Vision-Language Survival Analysis with Ordinal Inductive Bias for Computational Pathology [[paper]](https://openreview.net/pdf?id=trj2Jq8riA)[[code]](https://github.com/liupei101/VLSA?tab=readme-ov-file#-awesome-papers-of-pathology-vlms)  
   VLSA：面向计算病理学的可解释视觉-语言序贯生存分析框架（基于序数归纳偏置）  
7. [2025 CV] Tile-level Histopathology image Understanding benchmark [[paper]](https://arxiv.org/pdf/2507.07860)[[code]](https://github.com/MICS-Lab/thunder)    
   基于图像块的病理切片理解基准测试   
8. [2025 arXiv] Test-time Adaptation for Foundation Medical Segmentation Model Without Parametric Updates [[paper]](https://arxiv.org/pdf/2504.02008)  
   无需参数更新的基础医学分割模型测试时自适应方法  
9. [2025 arXiv] Test-time Adaptation for Foundation Medical Segmentation Model Without Parametric Updates [[paper]](https://arxiv.org/pdf/2504.02008)[[code]](https://github.com/ecoxial2007/Expert-CFG)  
   不确定性驱动的专家调控：增强医学视觉-语言模型的可靠性
10. [2025 arXiv] ModalTune: Fine-Tuning Slide-Level Foundation Models with Multi-Modal Information for Multi-task Learning in Digital Pathology [[paper]](https://arxiv.org/pdf/2503.17564)[[code]](https://github.com/ecoxial2007/Expert-CFG)   
   利用多模态信息微调玻片级基础模型实现数字病理中的多任务学习  
---

<a id="clip"></a>
## classic model

1. [2025 CVPR] COSMIC: Clique-Oriented Semantic Multi-space Integration for Robust CLIP Test-Time Adaptation [[paper]](https://arxiv.org/pdf/2503.23388) [[code]](待补充)  
   这篇论文提出了一种名为COSMIC（Clique-Oriented Semantic Multi-space Integration for CLIP）的新型测试时自适应（TTA）框架，旨在提升CLIP模型在新领域中的适应能力  
2. [2025-ICLR] EFFICIENT AND CONTEXT-AWARE LABEL PROPAGA TION FOR ZERO-/FEW-SHOT TRAINING-FREE ADAP TATION OF VISION-LANGUAGE MODEL [[paper]](https://arxiv.org/pdf/2412.18303) [[code]](https://github.com/Yushu-Li/ECALP)  
3. [2024-arXiv] Boosting Vision-Language Models with Transduction [[paper]](https://arxiv.org/pdf/2406.01837) [[code]](https://github.com/MaxZanella/transduction-for-vlms)  
   提出基于统计适应的转导推理方法，在11个跨模态基准测试中平均提升8.7%准确率  
4. [2025 arXiv] ViLU: Learning Vision-Language Uncertainties for Failure Prediction [[paper]](https://arxiv.org/pdf/2507.07620)[[code]](https://github.com/ykrmm/ViLU)  
   ViLU：基于视觉-语言不确定性学习的故障预测方法  
---

<a id="dataset-resources"></a>
## Dataset Resources

- **医学影像**  
  - [Medical Segmentation Decathlon](http://medicaldecathlon.com/) (多器官分割)  
  - [BraTS](https://www.med.upenn.edu/cbica/brats/) (脑肿瘤分割)  

- **通用视觉**  
  - [COCO](https://cocodataset.org) (开放词汇分割基准)
