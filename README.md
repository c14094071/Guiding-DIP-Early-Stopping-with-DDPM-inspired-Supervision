# Guiding-DIP-Early-Stopping-with-DDPM-inspired-Supervision
本repo涵蓋基於DIP基礎上增加DDPM噪音方法的實作，透過漸進式給予多到少噪音的圖片，藉以引導DIP學習噪音的特徵。第一部分Implementation(I).ipynb包含原始DIP與加上噪音所產生的問題，第二部分Implementation(II).ipynb則解決問題與最終結果。




## Image Dataset
[Mammals Image Classification Dataset (45 Animals)](https://www.kaggle.com/datasets/asaniczka/mammals-image-classification-dataset-45-animals?select=mammals)
    - 圖片大小為256X256
## Clone the repository
```bash=
git clone https://github.com/c14094071/Guiding-DIP-Early-Stopping-with-DDPM-inspired-Supervision.git
cd Guiding-DIP-Early-Stopping-with-DDPM-inspired-Supervision
```
## Installations

```bash=
pip install -r requirements.txt
```
## Usage
1. 若要直接查看最終成效，請直接查看Implementation(II).ipynb。
2. 本repo的ipynb都在colab上執行及使用雲端，執行前請確保你的圖檔路徑沒有問題。
3. 適當閱讀report.pdf
## Reference

1. DeepImagePrior- 
https://github.com/safwankdb/Deep-Image-Prior/tree/master
2. Denoising Diffusion Probabilistic Model-
https://www.kaggle.com/code/henrychibueze/denoising-diffusion-probabilistic-model/notebook
