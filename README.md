# StreamDETR: Exploring Robust Streaming Perception for Temporal Corruption
(简体中文版)[]

## ✨Abstract
Streaming perception is a critical task in autonomous driving, aiming to  eliminate the inconsistency between the perception results and the dynamic environment caused by inference delay. In practical scenarios, temporal corruption frequently occurs, including frame missing and frame rate reduction, which significantly impacts the model's perception performance. However, previous works have ignored the study of streaming perception models in the presence of temporal corruption. Therefore, we extend the streaming perception problem to incorporate temporal corruption and define relevant evaluation benchmarks accordingly. Additionally, we propose StreamDETR as a novel and robust model. The model combines Temporal Motion Feature (TMF) and Time-Aware Feature Predictor (TAFP) for accurate future feature prediction under temporal corruption conditions. Furthermore, Knowledge Distillation of Future Feature (KDFF) is employed to enhance learning performance when dealing with complex corrupted data. Compared to the strong baseline, extensive experiments demonstrate that our approach not only achieves state-of-the-art performance in normal streaming perception tasks, but also exhibits excellent robustness against temporal corruption challenges. In large-size input experiments, we achieve improvements of $sAP_{reduction}$ and $sAP_{miss}$ by 7.2\% and 9.6\% respectively.

> ⚠️ **Note: This project will be open-sourced after the associated paper is accepted for publication.**


## 📦 Features
- [ ] A streaming perception framework robust to temporal corruption
- [ ] Modular design with clear interfaces
- [ ] Support for custom datasets and evaluation metrics
- [ ] Comprehensive training and evaluation pipelines

  
## 🔧 Requirements
To run the code, you will need:

+ Python >= 3.8
+ PyTorch >= 1.10

Additional dependencies listed in requirements.txt

## 📚 Citation
If you find this work useful, please cite our paper:
> Waiting for official publication……
