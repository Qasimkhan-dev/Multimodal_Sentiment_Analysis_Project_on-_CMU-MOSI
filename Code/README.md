
# Code Directory

This folder contains the complete implementation of the proposed Multimodal Sentiment Analysis framework developed using PyTorch and evaluated on the CMU-MOSI dataset.

The codebase includes:

- Data preprocessing and loading pipelines
- Text, audio, and visual modality encoders
- BiLSTM temporal modeling
- Multi-head self-attention modules
- Cross-modal attention mechanisms
- Transformer-based multimodal fusion
- Dynamic context-aware gating
- Bilinear interaction layers
- Modality confidence estimation
- Focal Loss training strategy
- Missing-modality augmentation
- MC Dropout uncertainty estimation
- Training, validation, and evaluation scripts
- Ablation study implementations

The implementation is designed for research and experimentation in multimodal deep learning and uncertainty-aware sentiment analysis.

## Requirements

- Python 3.10+
- PyTorch 2.x
- NumPy
- scikit-learn
- matplotlib
- pandas

## Dataset

The experiments use the CMU-MOSI dataset with aligned text, audio, and visual features.

## Running the Project

Train the model:

```bash
python train.py
