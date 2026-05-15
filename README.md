# Enhanced Multimodal Sentiment Analysis using Cross-Modal Attention and Transformer Fusion

This repository contains the complete implementation, research paper, experimental results, and presentation for an advanced Multimodal Sentiment Analysis (MSA) framework developed on the CMU-MOSI benchmark dataset.

The project combines textual, acoustic, and visual information to predict human sentiment from opinion videos using deep learning and attention-based multimodal fusion techniques.

## Project Highlights

- Cross-Modal Attention across all modality pairs
- Transformer-based Fusion with CLS token
- BiLSTM Temporal Modeling
- Dynamic Context-Aware Gating
- Bilinear Cross-Modal Interaction
- Modality Confidence Estimation
- Focal Loss for class imbalance handling
- Missing-Modality Augmentation
- MC Dropout Uncertainty Estimation
- Nine-Variant Ablation Study

## Results

| Metric | Score |
|--------|--------|
| Acc2 | 74.2% |
| Acc3 | 66.3% |
| Weighted F1 | 65.9% |
| MAE | 0.453 |

The proposed framework achieves a **61% reduction in MAE** compared to the baseline model while improving sentiment classification performance and prediction reliability.

## Repository Structure

```text
├── code/              # Model implementation and training scripts
├── paper/             # IEEE research paper
├── presentation/      # Project presentation slides
├── figures/           # Training graphs and visualizations
├── results/           # Evaluation outputs and ablation studies
└── README.md
```

## Technologies Used

- Python
- PyTorch
- Google Colab
- CMU-MOSI Dataset
- OpenSMILE
- OpenFace
- GloVe Embeddings

## Dataset

Experiments were conducted on the CMU-MOSI dataset containing aligned text, audio, and visual features extracted from online opinion videos.


FAST-NUCES Islamabad — Department of Computer Science
