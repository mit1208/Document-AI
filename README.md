# Document AI: Advanced Layout Analysis & Multimodal Understanding

This repository showcases a series of advanced projects in **Document AI**, focusing on document layout analysis, multimodal grounding, and high-fidelity segmentation. Each notebook is designed for experimentation and can be launched directly in Google Colab.

---

## 🚀 Key Features

- **Document Layout Analysis**: Leveraging LayoutLMv3 and UDOP for structural understanding.
- **Segmentation**: Utilizing the Segment Anything Model (SAM) for granular document element identification.
- **Multimodal Grounding**: Fine-tuning KOSMOS-2 for vision-language tasks.
- **Hugging Face Integration**: Built primarily with the `transformers` and `datasets` libraries.

## 📊 Datasets & Models

| Component | Description |
| :--- | :--- |
| **Datasets** | Primarily [DocLayNet](https://huggingface.co/datasets/idsl/DocLayNet) |
| **Models** | [LayoutLMv3](https://huggingface.co/microsoft/layoutlmv3-base), [KOSMOS-2](https://huggingface.co/microsoft/kosmos-2-patch14-224), [SAM](https://huggingface.co/facebook/sam-vit-huge), [UDOP](https://huggingface.co/microsoft/udop-unlimited) |

---

## 📓 Notebooks

| Project | Description | Link |
| :--- | :--- | :--- |
| **LayoutLMv3 Fine-tuning** | Fine-tune LayoutLMv3 on DocLayNet using the HF Trainer. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mit1208/Document-AI/blob/main/FineTuning_LayoutLMv3_Trainer_HF_DocLayNet.ipynb) |
| **KOSMOS-2 Grounding** | Instruction tuning for multimodal grounding tasks. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mit1208/Document-AI/blob/main/Fine_tune_KOSMOS_2_for_multimodal_grounding.ipynb) |
| **LayoutLMv3 Inference** | Rapid inference and visualization script for LayoutLMv3. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mit1208/Document-AI/blob/main/LayoutLMv3_Inference.ipynb) |
| **SAM Segmentation** | Apply the Segment Anything Model to complex documents. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mit1208/Document-AI/blob/main/SAM_DocLayNet.ipynb) |
| **UDOP Encoder Tuning** | Fine-tune the Universal Document Processing encoder. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mit1208/Document-AI/blob/main/UDOPEncoderModel_fine_tune_DocLayNet.ipynb) |
| **UDOP Inference** | Inference and structural analysis using UDOP. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mit1208/Document-AI/blob/main/UDOP_DocLayNet_Inference.ipynb) |

---

## 🛠️ Requirements

Typical requirements across these notebooks include:
- `transformers`
- `datasets`
- `torch`
- `pillow`
- `accelerate`

Each notebook contains its own dependency installation cell for convenience.