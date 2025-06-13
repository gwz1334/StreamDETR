# StreamDETR: Exploring Robust Streaming Perception for Temporal Corruption
[简体中文版](https://github.com/gwz1334/StreamDETR/blob/main/README_CN.md)

## ✨Abstract
Streaming perception is essential for autonomous vehicles, addressing latency-induced discrepancies between perception outputs and rapidly changing environments. Real-world deployment often involves temporal corruption—such as frame loss or reduced frame rates—severely degrading model performance. Existing research largely overlooks streaming perception model robustness under such corruption. To bridge this gap, we formalize temporal corruption within the streaming perception paradigm and establish corresponding evaluation metrics. We introduce StreamDETR, a robust architecture designed for these challenges. StreamDETR integrates Temporal Motion Feature (TMF) with a Time-Aware Feature Predictor (TAFP) to achieve precise future feature forecasting despite corrupted inputs. It further incorporates Knowledge Distillation of Future Feature (KDFF) to improve learning efficacy on complex corrupted data. Comprehensive evaluations against strong baselines confirm our method sets new standards not only in conventional streaming perception but also demonstrates exceptional resilience to temporal corruption. For large-scale inputs, StreamDETR yields gains of 7.2% in $sAP_{reduction}$ and 9.6% in $sAP_{miss}$.

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
