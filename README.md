Medical Visual Question Answering with Vision-Language Models
This repository contains the implementation of our Medical VQA study comparing traditional CNN-LSTM architectures with modern vision-language models (CLIP) on the SLAKE dataset.

📁 Repository Contents

cnn_lstm_baseline.ipynb - CNN-LSTM baseline model implementation
clip_v1.ipynb - CLIP model with full 229-class vocabulary
clip_final_65_classes_.ipynb - CLIP model with vocabulary reduction (top-65 classes)

📊 Dataset
SLAKE (Semantically-Labeled Knowledge-Enhanced Dataset)

Access: [Hugging Face](https://huggingface.co/datasets/BoKelvin/SLAKE)
Content: Medical images (CT, MRI, X-ray) with bilingual VQA pairs
Filtered to English questions only
Train: 4,918 samples | Validation: 1,047 | Test: 1,059
