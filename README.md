# Neural Networks – Cats vs. Dogs Image Classification

Coursework project for the **Neural Networks** module (M.Sc., Justus Liebig University
Giessen & THM, 2021). We compared three ways of classifying cat and dog images:
a CNN built from scratch, transfer learning with a pretrained VGG16 in PyTorch,
and [transfer learning with fastai].

Final grade for the module: 15/15 points.

## Approaches

| Approach | Notebooks | Result |
|---|---|---|
| **CNN from scratch** | `Test1_CNN_From_Scratch`, `CNN_From_Scratch_Version_1/2`, `CNN_from_SCRATCH_Version_Jan` | 65 % accuracy |
| **CNN with dropout and learning rate tuning** | `CNN_Modell_Dropout_Lr` | 73 % |
| **Transfer learning (VGG16, PyTorch)** | `Dog_vs_Cat_transfer_pytorch_VGG16` | 83 % |

The notebooks show how the model evolved step by step: from a first baseline over
regularization (dropout) and learning rate tuning to transfer learning with a
pretrained network. Comparisons of the PyTorch transfer learning runs are in
`TransferLearning_Pytorch_Versionen.xlsx` and `NN_dc_tl_p_Accuracy`.

## Report

The full written report (German) with method, experiments and results:
`Abgabe_Hausarbeit_Neuronale_Netze.pdf`

## Data

`Data gekürzt.zip` contains a reduced subset of the
[Kaggle Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats) dataset
so the notebooks run quickly in Google Colab.

## Running the notebooks

All notebooks were written in **Google Colab**. Open one via
*File → Open notebook → GitHub*, upload `Data gekürzt.zip` and run all cells.

## Tech stack

Python · PyTorch · torchvision (VGG16) · [Keras/TensorFlow for the CNN from scratch] · [fastai] · Jupyter / Google Colab

---

Team project by Jan, Elisa and [Adrian Setka](https://www.linkedin.com/in/…).
