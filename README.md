# 基于深度学习的开集识别研究

# papers

### 不依赖辅助数据的开集识别

基于置信度校正的开集识别算法：

- ODIN(Enhancing the reliability of out-of-distribution image detection in neural networks)(ICLR 2018)[[CODE](https://github.com/facebookresearch/odin)](torch)
- NMD(Neural mean discrepancy for efficient out-of-distribution detection)(CVPR 2022)
- Energy(energy-based out-of-distribution detection)(NeurIPS 2020)[[CODE](https://github.com/wetliu/energy_ood)](torch)
- GEN(Gen: Pushing the limits of softmax-based out-of-distribution detection)(CVPR 2023)[[CODE](https://github.com/xixiliu95/gen)](torch)

基于距离的开集识别算法：

- OpenMax(Towards open set networks)(CVPR 2016)[[CODE](https://github.com/abhijitbendale/OSDN)](caffe)
- CROSR(Classification-reconstruction learning for open-set recognition)(CVPR 2019)[[CODE](https://github.com/saketd403/CROSR)](torch)
- MetaMax(MetaMax: Improved open-set deep neural networks via weibull calibration)(WACV 2023)
- CAC(Class anchor clustering: a loss for distance-based open set recognition)(WACV 2021)[[CODE](https://github.com/dimitymiller/cac-openset)](torch)
- CPN(Robust classification with convolutional prototype learning)(CVPR 2018)[[CODE](https://github.com/YangHM/Convolutional-Prototype-Learning)](tensorflow)
- RPL(Learning open set network with discriminative reciprocal points)(ECCV 2020)[[CODE](https://github.com/KevLuo/OpenSet_ReciprocalPoints)](torch)
- ARPL(Adversarial reciprocal points learning for open set recognition)(PAML 2021)[[CODE](https://github.com/iCGY96/ARPL)](torch)
- PMAL(Pmal: open set recognition via robust prototype mining)(AAAI 2022)
- CVAECapOSR(Conditional variational capsule network for open set recognition)(ICCV 2021)[[CODE](https://github.com/guglielmocamporese/cvaecaposr)](torch)
- MGPL(Learning multiple gaussian prototypes for open-set recognition)(Elsevier 2023)

基于重构的开集识别算法：

- C2AE(C2ae: class conditional auto-encoder for open-set recognition)(CVPR 2019)
- GFROR(Generative-discriminative feature representations for open-set recognition)(CVPR 2020)
- CGDL(Conditional gaussian distribution learning for open set recognition)(CVPR 2020)[[CODE](https://github.com/loganriggs/conditionalGaussionRecreation)](torch)
- MOODCAT(Out-of-distribution detection with semantic mismatch under masking)(ECCV 2022)[[CODE](https://github.com/cure-lab/moodcat)](torch)
- CSSR(Class-specific semantic reconstruction for open set recognition)(TPAMI 2022)

### 加入辅助数据的开集识别

基于离群值的开集识别算法：

- OECC(Outlier exposure with confidence control for out-of-distribution detection)(Neurocomputing 2021)[[CODE](https://github.com/nazim1021/OOD-detection-using-OECC)](torch)
- Agnostophbia(Reducing network agnostophobia)(NeurIPS 2018)[[CODE](https://github.com/Vastlab/Reducing-Network-Agnostophobia)](torch)
- MixOE(Mixture outlier exposure: Towards out-of-distribution detection in fine-grained environments)[[CODE](https://github.com/zjysteven/mixoe)](torch)

基于数据生成的开集识别算法：

- G-OpenMax(Generative openmax for multi-class open-set classification)(CVPR 2017)
- OSRCI(Open set learning with counterfactual images)(ECCV 2018)
- DIAS(Difficulty-aware simulator for open set recognition)(ECCV 2022)[CODE](https://github.com/wjun0830/difficulty-aware-simulator)(torch)
- PROSER(Learning placeholders for open-set recognition)(CVPR 2021)[CODE](https://github.com/zhoudw-zdw/CVPR21-Proser)(torch)
