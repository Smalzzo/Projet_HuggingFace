# 🧠 Projet de Segmentation Sémantique avec Hugging Face

Ce projet utilise un modèle pré-entraîné de type **Segformer** pour effectuer de la **segmentation d'images** (ex. vêtements). 
Il a été développé dans un notebook Google Colab dans le cadre d’un projet IA.

## 🔍 Objectif

Segmenter automatiquement les vêtements à partir d’images d’entrée, et évaluer les performances du modèle grâce aux métriques suivantes :
- **Pixel Accuracy (PA)**
- **Mean Intersection over Union (mIoU)**

## 📂 Contenu du projet

- `SegmentationFinal1.ipynb` : Notebook principal avec le code complet
- Visualisation des masques réels vs. prédits
- Calculs des métriques d’évaluation
- Visualisation des performances par image

## 📦 Modèle utilisé

- [`mattmdjaga/segformer_b2_clothes`](https://huggingface.co/mattmdjaga/segformer_b2_clothes)

## 🛠️ Installation (local)

```bash
pip install transformers datasets torch torchvision matplotlib scikit-learn
